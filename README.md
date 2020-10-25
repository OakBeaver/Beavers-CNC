# Beavers-CNC

This is a project of home made CNC which for now consists of ESC stack boards, magnetic encoder PCB and on-chip debugger board projects.

[**Alder-1**](https://github.com/OakBeaver/Beavers-CNC/tree/main/Module%20Alder-1%20E00001)


![Alder-1](https://raw.githubusercontent.com/OakBeaver/Beavers-CNC/main/Module%20Alder-1%20E00001/Module%20Alder-1%20E00001%20TOP.jpg?token=AKDAVB5EDELZYOSCXNLIOBS7SW7WO)

Module Alder-1 E00001 is a digital part of the ESC based on STM32F446 and DRV8305 and designed for FOC motor control. It has external communication via CAN, takes information from current sensors, motor and drive encoders and gives PWM to Oak-1. It monitors the temperature of the motor and the inverter onboard Oak-1 and provides fan control.


[**Oak-1**](https://github.com/OakBeaver/Beavers-CNC/tree/main/Module%20Oak-1%20E00003)

![Oak-1](https://raw.githubusercontent.com/OakBeaver/Beavers-CNC/main/Module%20Oak-1%20E00003/Module%20Oak-1%20E00003%20TOP.jpg?token=AKDAVBYWLOK7UHMGXEHDR327SW74A)

Module Oak-1 E00003 is the power part of the ESC and may differ for different motors and provides an external connection for Alder-1. It consists of a 3-phase inverter, current sensors, NTC and EEPROM for ESC stack configs in case of Alder-1 replacing.


[**Apple-1**](https://github.com/OakBeaver/Beavers-CNC/tree/main/Module%20Apple-1%20E00007)

![Apple-1](https://raw.githubusercontent.com/OakBeaver/Beavers-CNC/main/Module%20Apple-1%20E00007/Module%20Apple-1%20E00007%20TOP.jpg?token=AKDAVB4RMY26R3Y2G6S4CY27SW7Z6)

Module Apple-1 E00007 is a simple board for magnetic encoder AS5600 that operates via I2C. The magnet should be placed above the chip and mounted on the motor shaft or the drive gear axis.


[**Blackthorn-1**](https://github.com/OakBeaver/Beavers-CNC/tree/main/Module%20Blackthorn-1%20E00009)

![Blackthorn-1](https://raw.githubusercontent.com/OakBeaver/Beavers-CNC/main/Module%20Blackthorn-1%20E00009/Module%20Blackthorn-1%20E00009%20TOP.jpg?token=AKDAVBYICS6JMJ25OFULH7S7SW752)

Module Blackthorn-1 E00009 is an on-chip debugger PCB based on DAP-Link design with galvanic isolation. It supports SWD debugging and UART communication with the target and connect to the PC using USB cable.
