🇺🇸 English | 🇧🇷 [Português](README.pt.md)

# Surprise Interactive Project — Connect Byte 

A creative electronics experience where participants build a small interactive artifact, combining creativity, imagination, and hardware in a light and fun way.

This project was developed for a Connect Byte workshop and introduces fundamental electronics concepts through a practical and creative approach. 

---

## Overview 

In this workshop, participants will create a personalized interactive object using simple materials and electronic components. 

The experience happens in two stages: 
- a creative stage, focused on personalization and visual expression       
- a technical stage, where interaction is added with light and/or sound   

The final result is something that reacts to the user — transforming a static creation into something alive and surprising.

### Learning Objectives 
This project introduces: 
- basic electronics (Voltage, Current, and GND) 
- how LEDs work and why resistors are important 
- assembling simple circuits with a battery and a button 
- using sensors to capture environmental stimuli 
- creating interactions with Arduino 
- integration between art and technology 

---

## Circuit 

### Level 1 — Basic 
A simple interactive circuit using: 
- LED 
- coin cell battery (CR2032) 
- push-button 
- resistor 
- wires 

Basic logic: 
- Battery (+) → Button → Resistor → LED (+) 
- Battery (–) → LED (–) 

Behavior: 
- press → activates 
- release → deactivates 

### Level 2 — Intermediate 
An interactive system with Arduino: 
- Arduino (Nano or Uno) 
- sound sensor (KY-038) 
- buzzer 
- LED 
- resistors 
- wires 
- USB power 

Behavior: 
- detects environmental stimuli (e.g., sound) 
- processes with the Arduino 
- activates outputs (light + sound) 

---

## Code 

The example code is available in the `code` folder. 

Compatible with: 
- Arduino IDE 
- PlatformIO (VS Code) 

Main file: 
`code/src/main.cpp`

The code covers: 
- sensor reading 
- output control (LED + buzzer) 
- simple interaction logic 

### Workshop Experience 
This project was designed to be: 
- accessible for beginners 
- creative first, technical later 
- exploratory and fun 

No prior experience with electronics is required. 

---

## Connect Byte 
Website: https://connect-byte.org  
LinkedIn: https://www.linkedin.com/company/connect-byte/  
Instagram: [@connectbyte_](https://www.instagram.com/connectbyte_)
