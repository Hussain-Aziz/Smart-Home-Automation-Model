# Smart Home Automation Model

![rpi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white)
![py](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

This project uses a Raspberry pi 3B with various sensors for enhanced home security and environmental monitoring.

The home_system.py file is the code ran on the Raspberry pi to control the sensors and actuators. The code is multithreaded to allow for multiple sensors to be monitored at the same time. The system also uses a flask server to allow for remote monitoring of the system.

The sensors used were

- PIR Motion Sensor
- DH11 Temperature and Humidity Sensor
- Ultrasonic Sensor
- Push Button
- Camera Module
- KeyPad
- RFID
