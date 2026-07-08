# Smart Security and Automation System Using Dual Arduino

## Overview

This project is a dual Arduino Uno-based Smart Security and Automation System designed and simulated using Tinkercad. It uses a Master-Slave architecture to integrate multiple sensors and actuators for security, monitoring, and automation. The system combines password authentication, obstacle detection, environmental monitoring, visual and audible alerts, and DC motor control into a single embedded application.

---

## Features

- Password authentication using a 4×4 keypad
- 16×2 LCD display for user interaction
- Ultrasonic sensor for obstacle detection
- Temperature monitoring using TMP36 sensor
- Automatic light detection using LDR
- Buzzer alarm for alerts
- LED status indication
- Dual DC motor control using L293D motor driver
- Master-Slave communication between two Arduino Uno boards
- Designed and simulated in Tinkercad

---

## Components Used

- Arduino Uno (2)
- 16×2 LCD Display
- 4×4 Matrix Keypad
- HC-SR04 Ultrasonic Sensor
- TMP36 Temperature Sensor
- LDR (Light Dependent Resistor)
- L293D Motor Driver IC
- DC Motors (2)
- Buzzer
- LEDs
- Breadboards
- 9V Battery
- Jumper Wires

---

## Working Principle

1. The Master Arduino receives user input through the keypad.
2. The LCD displays system status and messages.
3. The ultrasonic sensor continuously measures the distance to detect nearby obstacles.
4. The TMP36 sensor monitors the surrounding temperature.
5. The LDR measures ambient light intensity.
6. The Master Arduino processes the sensor data and communicates with the Slave Arduino.
7. The Slave Arduino controls LEDs, buzzer, and DC motors according to the received commands.
8. The system provides both visual and audible indications while controlling the motors based on sensor inputs and user interaction.

---

## Software Used

- Tinkercad
- Arduino IDE
- Embedded C++

## Applications

- Smart Home Automation
- Access Control Systems
- Embedded System Learning
- Industrial Monitoring
- Security Systems
- IoT Prototype Development

---

## Future Enhancements

- Wi-Fi monitoring using ESP8266/ESP32
- Mobile application integration
- Cloud-based data logging
- GSM-based SMS alerts
- RFID or fingerprint authentication
- Voice control
- IoT dashboard for remote monitoring


## Author

**Chaitanya Malle**

B.Tech – Electronics and Communication Engineering

## License

This project is developed for educational and learning purposes.
