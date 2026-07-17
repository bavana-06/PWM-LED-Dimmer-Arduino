# PWM LED Dimmer using Arduino

## Project Overview
This project controls the brightness of an LED using Pulse Width Modulation (PWM). A potentiometer is used to adjust the brightness of the LED.

## Components Used
- Arduino Uno
- LED
- 220Ω Resistor
- Potentiometer
- Jumper Wires

## Software Used
- Wokwi Arduino Simulator

## Working Principle
The Arduino reads the potentiometer value using analogRead(). The value is converted from 0–1023 to 0–255 using the map() function. Then analogWrite() generates a PWM signal to control the LED brightness.

## Features
- LED brightness control
- PWM-based output
- Simulation using Wokwi

## Author
Bhavana R
B.E. Electrical and Electronics Engineering