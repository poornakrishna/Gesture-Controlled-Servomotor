# Gesture-Controlled-Servomotor
This project demonstrates gesture-based control of a servo motor using an MPU6050 accelerometer and an Arduino Uno. The system detects hand movements (tilts) and converts them into corresponding servo movements. This technique is widely used in robotics, prosthetics, and smart automation.

The Components that I have used are Arduino Uno, MPU6050, Servomotor.

In this system MPU6050 detects for tilts in x,y and z axis. These values are read by Arduino. Based on these tilt values Servomotor moves to 0, 90 and 180 degrees. This project can further be enhanced by using bluetooth module fto control servo wirelessly and use machine learning techniques for better gesture recognition. 
