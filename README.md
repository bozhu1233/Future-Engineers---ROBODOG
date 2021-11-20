# Future-Engineers---ROBODOG
The robot started with a while loop waiting for a signal coming from the ultrasonic sensor. The robot then calibrates its surroundings determining whether to go left or right. 

Camera 
With the library OpenCV, we are able to help the robot make its own decisions. Once the camera is opened a frame is captured constantly. The frame is then taken into the processing cycle. In this cycle the frame is converted from  RGB to HSV. An array of the HSV value of lower and upper red and lower and upper green checked to distinguish which colour it is. A mask is generated and only the desired colors will be shown. The colour is then matched with the contours making the pixels colorized. Grouping the pixel, we are able to draw a border around the colored pixels. 

Ultrasonic 
When activated a trigger sound wave is sent and received. The trigger sound wave bounces off a surface and comes back to an echo receiver. The time is recorded and a series of calculations is used to have a distance outcome.

Relay
The relay is plugged in and GPIO.high causes the motor to move and GPIO.low causes the motor to stop.

Servo
The servo is initialised as pwm. Change Duty Cycle shall send a voltage making the servo make.

Qualification
As the start key is received, the robot will switch the relay to high causing the motors to run. While running the ultrasonic sensor is processing the distance that the robot is from the wall. The robot then moves until the ultrasonic distance is less than 100cm. Following this, the robot begins to turn with the IMU to achieve 90 degree turn. After the robot has done this four times, it add 1 lap to the lap counter. When 3 laps are satisfied the relay switches to low making the robot stop.

Final
As the start key is received, the robot will switch the relay to high causing the motors to run. While running the ultrasonic sensor is processing the distance that the robot is from the wall. The camera is constantly on checking, whether there is a block, is a green block or is a red block. If the camera detects a block it determines the colour and avoids it. The robot then moves until the ultrasonic distance is less than 100cm. Following this, the robot begins to turn with the IMU to achieve 90 degree turn. After the robot has done this four times, it add 1 lap to the lap counter. When 3 laps are satisfied the relay switches to low making the robot stop.
                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     
                                                                                                                                                                                                                                                                                                                 
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     
                                                                                                                                                                                                                                                                                                                 
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     
                                                                                                                                                                                                                                                                                                                 
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     
                                                                                                                                                                                                                                              
