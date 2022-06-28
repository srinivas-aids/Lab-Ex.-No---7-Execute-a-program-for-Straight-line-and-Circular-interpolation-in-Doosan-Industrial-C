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
## program:
![image](https://user-images.githubusercontent.com/93427183/176112071-af3f33b3-5f44-4e53-8bad-828eec05dd26.png)
![image](https://user-images.githubusercontent.com/93427183/176112099-cc5adc72-e690-4ed9-bc82-fcb640c85471.png)
![image](https://user-images.githubusercontent.com/93427183/176112135-c99e9c16-f12e-4d9a-a858-5e5673f15b05.png)
![image](https://user-images.githubusercontent.com/93427183/176112173-7ca17489-5f75-4050-854d-d8132d6cd661.png)
![image](https://user-images.githubusercontent.com/93427183/176112191-ff06b4f2-470e-459c-88cf-74d42ab1f0ad.png)


### output

Linear Interpolation
![image](https://user-images.githubusercontent.com/93427183/176112232-a5d7bc58-a560-430f-be95-01ccb113eff08.png)
![image](https://user-images.githubusercontent.com/93427183/176112710-0c31d165-dd30-4ee4-987e-db01f0cac1a8.png)


Circular Interpolation
![image](https://user-images.githubusercontent.com/93427183/176112256-db09ceb2-7756-4b8a-b4b8-bd960c4eab68.png)

![image](https://user-images.githubusercontent.com/93427183/176113830-4f644785-542b-4f36-a4b3-5357228b1923.png)



### Results 
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully..


 
