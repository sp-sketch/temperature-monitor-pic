# temperature-monitor-pic
# Temperature Monitoring System using PIC18F452

## Overview
This project implements a real-time temperature monitoring system using a PIC18F452 microcontroller and LM35 analog temperature sensor. The measured temperature is displayed on a 16x2 LCD.

## Components Used
- PIC18F452 Microcontroller
- LM35 Temperature Sensor
- 16x2 LCD Display
- 7805 Voltage Regulator
- Crystal Oscillator (16 MHz)
- Passive components

## Working Principle
The LM35 outputs a voltage proportional to temperature (10 mV/°C).  
The PIC18F452 reads this voltage using its internal ADC and converts it into temperature data.  
The result is processed in embedded C and displayed on the LCD.

## Features
- Real-time temperature monitoring
- ADC-based sensing
- Embedded C implementation
- Expandable for IoT or data logging

## Applications
- Environmental monitoring
- Embedded systems learning
- Temperature logging systems

## Author
Siyon Peter  
B.Tech Electrical and Electronics Engineering  
NIT Calicut
