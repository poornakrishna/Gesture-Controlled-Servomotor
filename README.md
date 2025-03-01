# Gesture-Controlled-Servomotor
This project demonstrates gesture-based control of a servo motor using an MPU6050 accelerometer and an Arduino Uno. The system detects hand movements (tilts) and converts them into corresponding servo movements. This technique is widely used in robotics, prosthetics, and smart automation.

The Components that I have used are Arduino Uno, MPU6050, Servomotor.

In this system MPU6050 detects for tilts in x,y and z axis. These values are read by Arduino. Based on these tilt values Servomotor moves to 0, 90 and 180 degrees. This project can further be enhanced by using bluetooth module to control servo wirelessly and use machine learning techniques for better gesture recognition. 

Few real world applications are:
1. Prosthetic Limbs – Gesture-controlled prosthetic hands use similar sensor-based systems to interpret muscle or hand movements, allowing users to perform precise tasks like gripping or pointing.
2. Robotic Arms in Manufacturing – Factories use gesture-controlled robotic arms for tasks like assembly, welding, and packaging, reducing manual labor while improving precision and efficiency.
3. Smart Home Automation – This technology can be integrated into smart homes to control devices like lights, fans, and curtains with simple hand movements, enhancing accessibility and convenience.
4. Gaming and Virtual Reality (VR) – Gesture-based controls enhance gaming experiences by allowing players to interact naturally with virtual environments, improving immersion and engagement.
