# Pixelate_TECHNEX2019
The first prize winning solution of Pixelate -an image processing event ,with a hardware implementation for a ludo like maze, Technex 2019, IIT (BHU) Varanasi.

## Problem Statement:
Pixelate of Technecx2019 ,expected us to develop a robot for playing a ludo like game using the live feed from a over-head web cam.
The detailed PS: 

## Our Solution:
 
* We used OpenCV for the shape detection and colour detection and then used it to get to the nearest shape as given out by  the die roll.
* Then an optimal graph/path was plotted to get the optimal trajectory ,connecting the centroids of all the shapes along the way to the destination shape.
* Once the path was recieved we used PID to make our robot to follow the line conecting all this dots. Individual PID parameters were used to make the robot to go straight and as well take sharp 90 degree turns.

## Our Final Run: [Watch the video](https://drive.google.com/file/d/120BLAxGn3nnFRBQjH3iGT_9vKcmoUdTq/view?usp=sharing)

## Background processing:
![Screenshot](https://github.com/wikkieritz/PIXELATE_TECHNEX2019/blob/master/Images/ScreenShot.jpg)

Robot Used:
![Robot](https://github.com/wikkieritz/PIXELATE_TECHNEX2019/blob/master/Images/robot_used.jpg)
