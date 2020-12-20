# Moving-Target

You are at the shooting gallery again and you need a program that helps you keep track of moving targets. On the first line, you will receive a sequence of targets with their integer values, split by a single space. Then, you will start receiving commands for manipulating the targets, until the "End" command. The commands are the following:
Shoot {index} {power}
Shoot the target at the index, if it exists by reducing its value by the given power (integer value).A target is considered shot when its value reaches 0.
Remove the target, if it is shot.
Add {index} {value}
Insert a target with the received value at the received index, if it exist. If not, print: "Invalid placement!"
Strike {index} {radius}
Remove the target at the given index and the ones before and after it depending on the radius, if such exist. If any of the indices in the range is invalid print:
"Strike missed!" and skip this command.

 Example:  Strike 2 2
	{radius}	{radius}	{strikeIndex}	{radius}	{radius}		

End
Print the sequence with targets in the following format:
{target1}|{target2}…|{targetn}
