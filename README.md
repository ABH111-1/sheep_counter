# sheep_counter
RoboVITics Electrical Assignment

Problem Statement: 
Imagine a flock of sheep, one by one moving in and out of a fenced grassland. 
Now the shepherd wants a device attached to the fence door that keeps track of the number of sheep inside the land.
So your task is to create a Tinkercad simulation of a device that is suitable for this job.

Solution:
To track the entry and exit of sheep through a fenced grassland, the shepherd can use two PIR sensors and an Arduino Uno R3 to detect the motion of sheep in and out of the grassland.
Placing one sensor towards the outside of the grassland and one on the inside, and calling them entry and exit sensors respectively, the Arduino can check the outputs of the sensors and compare their values with each other in two orders:
1. The entry sensor giving a HIGH and then momentarily the exit sensor giving a HIGH indicates that a sheep has entered the fenced grassland.
2. The exit sensor giving a HIGH and then momentarily the entry sensor giving a HIGH indicates that a sheep has exited the fenced grassland.

This way, the Arduino can then store the count of sheep inside the grassland.
The shepherd can further install a LCD display to display the number of sheep present in the grassland.
