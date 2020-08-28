# 16channel_PWM_servo
The 16-Channel PWM/Servo Driver will drive up to 16 servos over I2C with only 2 pins. 
The on-board PWM controller will drive all 16 channels simultaneously with no additional Arduino processing overhead.  You can chain up to 62 of them to control up to 992 servos. all with the same 2 pins.

Here you can find 3 different test codes
### 1. Test-1  
moving servos one by one from 1 to 16 
 PCA9685 takes only pulse to rotate servo 
 we create angletopulse function to convert our angle 
 to pulse
### 2. Test-1  
moving servos individually
 PCA9685 takes only pulse to rotate servo 
 we create angletopulse function to convert our angle 
 to pulse
### 3. Test-1  
moving all servos  at a single time
 PCA9685 takes only pulse to rotate servo 
 we create angletopulse function to convert our angle 
 to pulse
