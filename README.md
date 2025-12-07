# VoiceControlled-SmartWheelchair
A Smart Wheelchair system designed to provide safe and independent mobility for physically challenged and elderly people. The wheelchair is controlled wirelessly using a Bluetooth mobile app and also supports voice commands. An ultrasonic sensor is used for automatic obstacle detection to prevent collisions.

📌 Project Description
This project demonstrates the implementation of a low-cost Smart Wheelchair using Arduino UNO, HC-05 Bluetooth module, L298N motor driver, and an ultrasonic sensor.
The wheelchair can move in all four directions—forward, backward, left, and right—through a mobile Bluetooth app.
Additionally, the ultrasonic sensor detects nearby obstacles and automatically stops the wheelchair to prevent accidents.
This project is helpful in real-world applications like hospitals, rehabilitation centers, elderly homes, and personal use for differently-abled individuals.

🚀 Features
	•	Wireless Bluetooth control
	•	Voice command support
	•	Automatic obs!tacle detection
	•	Low-cost and beginner-friendly design
	•	Smooth directional movement
	•	Safety stopping mechanism
	•	Easy to expand with IoT / GPS / AI

🔧 Components Used
	•	Arduino UNO
	•	HC-05 Bluetooth Module
	•	L298N Motor Driver
	•	HC-SR04 Ultrasonic Sensor
	•	DC BO Motors & Wheels
	•	12V Battery
	•	Buck Converter (12V → 5V)
	•	Jumper Wires, Chassis, Breadboard

🛠 How the System Works
	1.	The user sends control commands (Forward/Backward/Left/Right/Stop) through a Bluetooth mobile app.
	2.	The HC-05 Bluetooth module receives the command and sends it to Arduino.
	3.	Arduino processes the data and controls the motor direction using the L298N driver.
	4.	The ultrasonic sensor continuously checks for obstacles ahead.
	5.	If an object is detected within a set distance, the Arduino immediately stops the motors to avoid collisions.  
  ![smart wheelchair output](https://github.com/user-attachments/assets/e8c49f0e-dadb-433e-8f6c-de64fd1fd6cb)
  

https://github.com/user-attachments/assets/d8bf143a-027c-4682-bb70-aee7638bf6de

![Wheelchair CIrcuit Diagram](https://github.com/user-attachments/assets/2a43a0f2-2511-4108-92a4-4e98996dd44a)

📄 Conclusion
The Smart Wheelchair project successfully demonstrates how embedded systems and wireless communication can be combined to create an efficient mobility-assistive device.
It improves safety, independence, and ease of movement for people with disabilities.

