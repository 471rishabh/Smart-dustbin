# Smart-dustbin
This project features a smart dustbin with an automatic waste compactor to reduce the volume of dry waste. It uses an N20 DC gear motor and linear actuator controlled by an Arduino. It includes an ultrasonic sensor and LCD display. Code and 3D printing files available.

# How it Works
The system works by measuring the distance of an object using the ultrasonic sensor. If the distance is less than 50cm, the system checks the moisture level of the waste using the moisture sensor. If the moisture level is above a certain threshold, the system opens the wet waste bin lid using the servo motor. If the moisture level is below the threshold, the system opens the dry waste bin lid using the servo motor.

## Required components
- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- Moisture Sensor
- IR Sensor
- Servo Motor
- LCD Display
- Breadboard
- Jumper Wires
- Installation

# Installation
1. Connect the ultrasonic sensor to the Arduino Uno as follows:
- VCC - 5V
- GND - GND
- Trig - Pin 6
- Echo - Pin 7
2. Connect the moisture sensor to the Arduino Uno as follows:
- VCC - 5V
- GND - GND
- A0 - Pin A0
3. Connect the IR sensor to the Arduino Uno as follows:
- VCC - 5V
- GND - GND
- OUT - Pin 8
4. Connect the servo motor to the Arduino Uno as follows:
- VCC - 5V
- GND - GND
- Signal - Pin 9 (for wet waste bin) and Pin 10 (for dry waste bin)
5. Connect the LCD display to the Arduino Uno as follows:
- VSS - GND
- VDD - 5V
- VO - Pin 3
- RS - Pin 12
- RW - GND
- EN - Pin 11
- D4 - Pin 5
- D5 - Pin 4
- D6 - Pin 3
- D7 - Pin 2
6. Upload the code to the Arduino Uno using the Arduino IDE.

- Power up the system and test it out!

# Contributing
Contributions are welcome! If you have any suggestions or improvements, please feel free to create a pull request.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.
