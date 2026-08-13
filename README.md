# Designing-a-PCB

# Overview

This board was designed to be the central control unit for a small robotic dog. It takes a single 3.7V LiPo cell as input, boosts it to a higher voltage for driving the leg servos, and uses an Arduino Nano to coordinate movement based on feedback from an onboard 6-axis IMU (MPU6050).


# Features

Microcontroller: Arduino Nano (ATmega328)

Power input: Single-cell 3.7V battery via dedicated connector

Power switch: Dedicated on/off switch connector

Voltage booster: MT3608 2A boost converter module for stepping up battery voltage to power the servos

4x servo headers: One 3-pin header per leg, for easy connection of standard hobby servos

IMU sensor: MPU6050 (accelerometer + gyroscope) connected via I2C for balance sensing
Double layer PCB with clearly labeled, logically arranged components.

# PCB Design
Layers: Double-layer (2-layer) PCB

Design tool: EasyEDA

Components are arranged for a clean, logical signal flow: power input/regulation on one side, microcontroller in the center, servo and sensor headers grouped along the edges for easy wiring to the robot's legs and body.
