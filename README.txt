
# Smart Sensor Monitoring and Alert System

## Overview
An embedded project that measures object distance
using an ultrasonic sensor and activates an alert
when an object approaches a defined threshold.

## Objectives
- Read distance from an HC-SR04 sensor.
- Process sensor data on a microcontroller.
- Display measurements over serial communication.
- Trigger an LED and buzzer for close objects.

## Hardware
- Arduino Uno
- HC-SR04 ultrasonic sensor
- LED and 220-ohm resistor
- Buzzer

## Software
- Arduino IDE
- C++ / Arduino framework
- Wokwi simulator

## How It Works
The microcontroller triggers the ultrasonic sensor,
measures the echo duration, calculates distance,
and activates the alert when distance is below 20 cm.

## Testing
Document tests at different distances, expected
outputs, actual outputs, and any issues fixed.

## Future Improvements
- Port to ESP32 or STM32.
- Add I2C OLED display.
- Explore interrupt-based timing.
- Add more robust sensor error handling.

## Simulation
Add your Wokwi simulation link here.


