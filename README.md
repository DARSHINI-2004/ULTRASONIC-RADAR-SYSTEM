# Arduino RADAR Model using Ultrasonic Sensor

## Overview
The Arduino RADAR Model is a prototype radar system designed for detecting and measuring objects using an ultrasonic sensor. This project leverages an Arduino Uno, ultrasonic sensor, and servo motor to create a radar-like system capable of detecting both stationary and moving objects within a 180-degree sweep. It is an excellent introduction to object detection and distance measurement using Arduino.

## Abstract
The RADAR system uses an ultrasonic sensor to measure distances and detect objects. By rotating the sensor with a servo motor, the system provides real-time distance measurements and visual feedback through an LCD display. This project demonstrates the integration of various electronic components to build a functional object detection system.

## Key Features
- **Ultrasonic Sensor**: Measures distances by emitting and receiving ultrasonic waves.
- **Servo Motor**: Rotates the ultrasonic sensor across a 180-degree range.
- **LCD Display**: Shows the distance and angle of detection, providing intuitive feedback.
- **Buzzer and LEDs**: Indicate the proximity of detected objects with sound and light signals.

## Hardware Components
1. **Arduino UNO Board**
2. **Ultrasonic Sensor HC-SR04**
3. **16x2 LCD Display**
4. **Potentiometer 10K**
5. **Servo Motor SG90**
6. **Buzzer 5V**
7. **LED 5mm (Any Color)**
8. **Connecting Wires**
9. **Breadboard**

## Circuit Diagram
Refer to the provided circuit diagram for wiring connections between the Arduino, ultrasonic sensor, servo motor, LCD, buzzer, and LEDs.

## Program/Source Code
Please refer to the provided source code for implementation details.

## Working of the Project
- **Signal Transmission**: The Arduino sends a signal to the ultrasonic sensor, which generates ultrasonic waves.
- **Object Detection**: The sensor measures the time it takes for the waves to return, calculating the distance to the object.
- **Servo Rotation**: The servo motor rotates the sensor, allowing it to scan a 180-degree area.
- **Display and Feedback**: Distance and angle data are shown on the LCD, while the buzzer and LEDs provide additional feedback on object proximity.

## Future Enhancements
- **Advanced Sensors**: Upgrade to more accurate sensors like the TFMini-S LiDAR for extended range and precision.
- **Integration**: Combine with other systems for enhanced functionalities in robotics and automation projects.

## References
- [Distance Measurement Using Arduino & HC-SR04 Ultrasonic Sensor](#)
- [Arduino Ultrasonic Range Finder with HC-SR04 on OLED Display](#)
