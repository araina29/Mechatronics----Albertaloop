# Team Spoilers Arduino Project

## Overview

This project documents the development of an Arduino-based robot car created as part of Team Spoilers' participation in the Alberta Loop Hackathon. The robot was engineered to master a series of challenging tasks, including navigating a maze, maintaining stability on a balance beam, and performing an RFID scan.

## Project Details

### Hardware Components

- Arduino board
- IR receiver
- Proximity sensor
- Motor driver
- Motors and wheels for movement

### Software Components

- Arduino IDE for programming the Arduino board
- IRremote library for interfacing with the IR receiver

## Functionality

The robot is controlled by an IR remote and is capable of the following functionalities:

1. **Task 1: IR Remote Control**
   - The robot can be controlled using an IR remote.
   - It responds to various IR commands for actions such as moving forward, reversing, stopping, and turning.

2. **Task 2: Proximity Detection**
   - The robot is equipped with a proximity sensor.
   - It can detect obstacles in its path and adjust its movement accordingly.

3. **Task 3: Motor Control**
   - The robot's motors are controlled based on the received IR commands.
   - It can move forward, reverse, or stop as per the commands received.

## Getting Started

To replicate this project or modify the code, follow these steps:

1. **Hardware Setup**
   - Connect the Arduino board to the necessary hardware components as described in the code comments.

2. **Software Setup**
   - Install the Arduino IDE if not already installed.
   - Open the provided Arduino sketch (`team_spoilers_robot.ino`) in the Arduino IDE.

3. **Upload Code**
   - Upload the code to the Arduino board using the IDE.

4. **Testing**
   - Power on the robot and test its functionalities using an IR remote.


## YouTube Demo

Check out the [YouTube video](https://youtube.com/shorts/wNF0cUexMdw?feature=share) demonstrating the robot's functionality.

## Contributors
- Aryaman Raina 
- Agrim Sood
- Falak Sethi 
- Shreyank Hebbar 
