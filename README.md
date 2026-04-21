<img width="805" height="871" alt="Screenshot 2026-04-18 005823" src="https://github.com/user-attachments/assets/2b64b43b-df23-458c-8fb2-09b18f6675b9" />
Shuriken – STM32G4 Dual FOC ESC Development Board

Shuriken is an STM32G4-based dual-channel Field-Oriented Control (FOC) Electronic Speed Controller development board designed for high-performance BLDC/PMSM motor control in robotics and aerial systems.

The board integrates two independent three-phase motor drivers on a single PCB, enabling simultaneous control of two motors while sharing processing and power infrastructure.

At the core of the system is the
STM32G474RE,
which provides a 170 MHz Cortex-M4F core, high-resolution timers, and synchronized ADCs optimized for real-time motor control.

Each motor channel is driven by the
DRV8323S-RTAT
smart gate driver, which controls an external MOSFET three-phase inverter and provides integrated current-sense amplifiers, SPI configuration, and hardware protection features.

Features

Dual three-phase BLDC/PMSM motor control

Field-Oriented Control (FOC) capable hardware platform

STM32G4 High-Resolution Timer (HRTIM) for precise PWM generation

Integrated current sensing and fault protection

SPI-configurable gate driver

Designed for motor control experimentation and development

Status

Hardware design and prototype bring-up are complete.
The FOC firmware and control stack are currently under active development.

Feedback

Constructive criticism, suggestions, and contributions are welcome.
