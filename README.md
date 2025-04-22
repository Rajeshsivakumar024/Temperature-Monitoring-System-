# Task 3: Temperature Monitoring System

## Description
This project uses the LM35 temperature sensor and PIC16F877A microcontroller to continuously monitor and display the temperature. It was built as part of my Embedded Systems Internship with Elite Tech Intern.

## Components Used
- PIC16F877A Microcontroller
- LM35 Temperature Sensor
- LCD Display (16x2)
- Resistors
- MPLAB X IDE

## Circuit Diagram
![Circuit](circuit.png)

## Code
See [main.c](main.c)

## Working
- LM35 outputs analog voltage based on temperature
- PIC reads this voltage via ADC and calculates temperature
- The temperature is displayed on an LCD

## Author
Rajesh
