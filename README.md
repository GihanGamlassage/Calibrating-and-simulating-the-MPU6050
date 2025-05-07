# Calibrating-and-simulating-the-MPU6050
The MPU-6050 is a 6-axis(combines 3-axis Gyroscope, 3-axis Accelerometer) motion tracking devices. Changes in motion, acceleration and rotation can be detected

Follow these steps,

Firstly, connect the MPU6050 to Arduino nano/uno board
So Vcc to 5V,GND to GND,SCL to A5 and SDA to A4
After that, you need to  upload the above "calibration" code to Arduino board
Its take some time
#Remember: When you upload the calibration code, you must place the sensor on a flat surface and do not move it.
Now calibration is completed

If you need to get the x,y, and z angles You can upload "Get angles"code to arduino.
But you are responsible for installing the necessary libraries. Like "mpu_light.

If you want to animate it . I Used Processing (Arduino + Java-based visualization)
 Steps:
       Install Processing IDE: https://processing.org/download
       Connect Arduino to PC and upload your MPU6050 code
       Create a new Processing sketch and paste the code "Simulation" in above.
       Important: Replace "PORT number" with the actual port your Arduino is connected to. You can find it in the Arduino IDE under Tools → Port.
NOw you can simulate it.       
       
