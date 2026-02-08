# STM32 PWM DC Motor Control with Temperature Monitoring (LM35 + LCD)

## Overview
This project implements a DC motor speed control system using an STM32F401RE microcontroller. 
The motor speed is controlled using PWM, while temperature is monitored using an LM35 sensor and displayed on a 16x2 LCD. 
An L293D motor driver is used to interface the motor with the microcontroller.

The project demonstrates timer configuration, ADC interfacing, PWM generation, sensor data acquisition, and peripheral interfacing in embedded C.

---

## Hardware Used
- STM32F401RE (Nucleo Board)
- L293D Motor Driver IC
- 12V DC Motor
- LM35 Temperature Sensor
- 16x2 LCD Display (HD44780)
- External 12V Supply

---

## Features
- PWM based motor speed control using Timer
- ADC based temperature sensing (LM35)
- Real-time temperature display on LCD
- Peripheral configuration using STM32CubeIDE
- Modular Embedded C code structure

---

## Working Principle
1. STM32 generates PWM signal using Timer to control motor speed.
2. L293D driver amplifies the signal to drive the DC motor.
3. LM35 outputs analog voltage proportional to temperature.
4. ADC converts analog voltage to digital value.
5. STM32 processes temperature data.
6. Temperature is displayed on 16x2 LCD in real-time.
7. The motor speed is controlled asper the temperature ranges.

---

## Peripherals Used
- GPIO
- ADC
- TIM (PWM mode)
- LCD (8-bit interface)

---

## Software & Tools
- STM32CubeIDE
- Embedded C
- CubeMX Configuration

---

## Applications
- Temperature monitored motor systems
- Cooling fan controllers
- Industrial motor protection systems
- Smart embedded control systems

---

## Author
Omkar Jadhav
