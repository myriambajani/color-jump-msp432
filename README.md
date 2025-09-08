# Color Jump Game
This project is a game I built on the **MSP432 microcontroller** using **C in Code Composer Studio (CCS)**. 
The goal is to keep the player alive by making sure their color matches the floor they’re running on, while avoiding barriers and racking up points.  

## Features
- Title, Menu, Options, Instructions, and High Score screens  
- Joystick controls for color swapping and movement  
- Boosterpack buttons for navigation and actions  
- Game logic written in C with a clean HAL (hardware abstraction layer)  
- Bonus features:
  - Custom Title Screen and Game Over Screen
  - 8-color wheel with diagonal joystick inputs  
  - Random barriers to jump over  
  - Mixed Mode: speed and points scale over time  

## Tools & Hardware
- **Language:** C  
- **IDE:** Code Composer Studio (CCS)  
- **MCU:** TI MSP432 LaunchPad  
- **Display:** LCD BoosterPack via SPI  

## References
See technical write up with inserted pictures in [report.pdf](./report.pdf).  
