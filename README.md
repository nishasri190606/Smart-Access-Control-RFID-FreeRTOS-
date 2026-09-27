# Smart Access Control System Using RFID with RTOS-Based Task Scheduling

## Project Overview

This project implements a Smart Access Control System using an RFID reader and FreeRTOS-based task scheduling.

The system performs RFID authentication and controls door access using separate RTOS tasks.

## Main Features

- RFID card detection using RC522
- RFID authentication
- LCD status display
- Door control
- Buzzer indication
- FreeRTOS task scheduling
- Inter-task communication using queues
- LCD synchronization using mutex

## Hardware / Simulation Platform

- STM32F103C8T6
- RC522 RFID Reader
- 16x2 I2C LCD
- Buzzer
- Door/Lock control output
- FreeRTOS
- STM32CubeIDE

## RTOS Tasks

1. RFID Task
2. Authentication Task
3. Door Control Task
4. LCD Task

## Communication

- RFID Queue
- Authentication Queue
- LCD Mutex

## Pin Configuration

| Device | STM32 Pin |
|---|---|
| RC522 SCK | PA5 |
| RC522 MISO | PA6 |
| RC522 MOSI | PA7 |
| RC522 SS | PA4 |
| RC522 RST | PB0 |
| LCD SCL | PB6 |
| LCD SDA | PB7 |
| Door Control | PA0 |
| Buzzer | PA1 |

## Project Objective

To demonstrate device driver development and real-time task scheduling using FreeRTOS in an RFID-based access control system.
