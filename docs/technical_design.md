# Technical Design

## Mechanical Design

The orthosis concept uses a neoprene support section for comfort and adaptability. ABS 3D-printed components were considered for the structural base because of their mechanical resistance.

## Sensor System

The prototype concept uses flexible sensing elements and an MPU6050 module. The flexible sensor component was intended to provide movement or force-related information, while the MPU6050 was intended to estimate wrist angle and motion.

## User Interface

An OLED 128x64 display was proposed to show local measurements from the device.

## EMG Acquisition Concept

The EMG section was designed to acquire forearm muscle activity. The circuit concept included signal amplification, filtering, offset conditioning, and rectification/mean absolute value processing.

## Data Flow

1. Sensors capture wrist/finger movement or muscle activity.
2. Arduino Nano reads analog/digital signals.
3. Data are processed locally or transmitted to a computer.
4. Measurements support rehabilitation assessment and progress monitoring.
