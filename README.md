# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.
### Output : 
![image](https://user-images.githubusercontent.com/94836154/176933485-88e0ff83-c912-4080-b62e-56e0743812f9.png)
![image](https://user-images.githubusercontent.com/94836154/176933520-d1838cee-a33d-4d71-a46b-d36b79045c9b.png)
![image](https://user-images.githubusercontent.com/94836154/176933570-346f25c8-fa6a-4fea-ac0e-fe5a87faa1b7.png)
![image](https://user-images.githubusercontent.com/94836154/176933600-9c24a138-2d99-4d75-a841-824a1343b721.png)
![image](https://user-images.githubusercontent.com/94836154/176933623-a8c15b6f-76a7-4078-bc9a-2a413c434413.png)
![image](https://user-images.githubusercontent.com/94836154/176933640-df3e96e5-fdbf-4ae0-9ec9-e47141f0094a.png)
![image](https://user-images.githubusercontent.com/94836154/176933786-21d05b5e-e60a-49dd-8f93-31272c0bd62b.png)
### Robot : 

### Linear Interpolation :

![image](https://user-images.githubusercontent.com/94836154/176934064-ceb5e871-07bf-4da6-8997-f9a03971844b.png)

### Circular Interpolation :

![image](https://user-images.githubusercontent.com/94836154/176934135-46cbbaa2-3e2e-4957-822e-332cd38dd9e9.png)

### Results :
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.



 
