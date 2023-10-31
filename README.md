# SortingDisks

This repository only contains videos of the robot, as the code is no longer accessible.

Disks are stacked on top of each other over the color determination zone.
The robot shines an initial light to detect the presence of a disk. This presence is detected by a light positioned directly opposite a light receiver. 
The disk drops between the two and the light receiver no longer detects any light, indicating a disk is ready for color determination.

The color determination is done with a secondary light positioned at an angle, close to the light receiver. The light shines on the disk and is reflected into the light receiver.
If a lot of light is reflected the light is determined to be white, otherwise it is indicated as black.
Once the color is determined the robot slides the disk to the respective disk color basket. 
As the disk slides into its basket, another disk from the stack takes its place and the cycle continues.
