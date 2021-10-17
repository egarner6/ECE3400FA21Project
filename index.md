## Welcome to my ECE 3400 Lab 1!

For this lab, I worked with my partner to assemble the robot, code it to drive a simple loop on the floor, and incorporate Ultrasonic Sensors to navigate a maze of blocks. To do this, Sergio and I programmed our robot to drive forward until the front sensor triggered. Then, the robot would evaluate the side sensors' readings and choose the side that had a further distance reading. From there, the robot would turn 90 degrees to the direction. In the case that all sensors trigger, the robot has reached a dead-end and needs to turn around completely. If all three sensors read high distance readings (ie wider than the maze path), then the robot did a 540 degree turn. We selected this method as it was important to utilize all three sensors in our design, instead of just using the front sensor.

Some problems we faced were mostly assembly and parts related. Our caster ball often got coated in dirt from running on the ground so we had to clean it frequently or use it on a table. As well, our wheels turned at different rates, so we had to adjust their speeds accordingly. Lastly, we had trouble with our Ultrasonic Sensor readings. At seemingly random, the sensors would read unreasonable values. To combat this, the sensors took a rolling average and whenever there was a value that was abnormal, it stopped to "think" and take more values. This is evident in our video as the robot occasionally stops.


Below is a video of the robot running through the maze and turning around at the end:
[Lab 1 Final Video](https://youtu.be/hTH1iRYtUkw)

## The robot in position 1:
<img src="https://github.com/egarner6/ECE3400FA21Project/blob/main/IMG_0902.PNG" alt="Position 1">

## The robot in position 2:
<img src="https://github.com/egarner6/ECE3400FA21Project/blob/main/IMG_0903.PNG" alt="Position 2">

## The robot in position 3:
<img src="https://github.com/egarner6/ECE3400FA21Project/blob/main/IMG_0905.PNG" alt="Position 3">

## The Serial Monitor:
<img src="https://github.com/egarner6/ECE3400FA21Project/blob/main/Serial%20Lab%201%20emg229%20spd75.jpg" alt="Serial Monitor">
