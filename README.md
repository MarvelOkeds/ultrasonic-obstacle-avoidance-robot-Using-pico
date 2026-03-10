# Raspberry Pi Pico Obstacle Avoidance Robot

## Overview
This project implements an autonomous obstacle avoidance robot using a Raspberry Pi Pico microcontroller and ultrasonic sensor. The robot detects obstacles and automatically changes direction to avoid collisions.

## Hardware Components
- Raspberry Pi Pico
- HC-SR04 Ultrasonic Sensor
- L298N Motor Driver
- DC Motors
- Robot Chassis
- Battery Pack

## How It Works
The ultrasonic sensor measures distance to obstacles. When an object is detected within a defined threshold distance, the robot stops and changes direction to avoid the obstacle.

## Programming
The robot is programmed using MicroPython.

## Future Improvements
- Add servo scanning
- Implement smarter navigation
- Add mapping capability
