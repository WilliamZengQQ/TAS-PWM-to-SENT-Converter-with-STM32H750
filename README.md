# TAS-PWM-to-SENT-Converter-with-STM32H750
An STM32H750VBT6-based project to convert four TAS sensor PWM signals into two SENT outputs, with timer input capture, signal validation, and timeout detection.

This project aims to develop a PWM-to-SENT converter for a Torque and Angle Sensor (TAS), using an STM32H750VBT6 microcontroller.
The converter will capture four PWM inputs—T1, T2, P, and S—and encode the required data into two SENT output channels for a receiving controller.
Current development focuses on:
- Timer-based PWM acquisition using STM32 HAL.
- Period and pulse-width measurement.
- Frequency and duty-cycle validation.
- Per-channel status tracking and timeout detection.
T1 acquisition and validation code has been implemented and compiled, and T2 support is being added. Hardware testing is pending. SENT output implementation remains planned, subject to confirmation of the receiving controller’s protocol requirements.
This project also serves as a hands-on learning exercise in embedded system architecture, peripheral configuration, interrupt handling, and modular firmware design.
