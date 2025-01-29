# Line-Following Robot Project

## Overview

This project showcases the development of a line-following robot utilizing the STM32F411CE microcontroller. The robot is equipped with TCRT5000 infrared sensors for line detection, an L298N dual DC motor driver for motor control, N20 gear motors for movement, and a LiPo battery as its power source.

A custom PCB was meticulously designed using Altium Designer and fabricated with a Cirqoid PCB milling machine. The firmware was developed in STM32CubeIDE, featuring a generalized line-following algorithm implemented through a manually tuned PID control system. Additionally, a Bluetooth module is integrated, allowing for remote control capabilities.

Future work aims to enhance the robot's performance through system identification using MATLAB and the application of advanced control strategies.

## Features

- **Microcontroller:** STM32F411CE
- **Sensors:** TCRT5000 infrared sensors for line detection
- **Motor Driver:** L298N dual DC motor driver
- **Motors:** N20 gear motors
- **Power Supply:** LiPo battery
- **PCB Design:** Custom-designed using Altium Designer
- **PCB Fabrication:** Fabricated with a Cirqoid PCB milling machine
- **Programming Environment:** STM32CubeIDE
- **Control System:** Manually tuned PID control
- **Communication:** Bluetooth module for remote control

## Repository Contents

- **Diagram/**: Schematics and system diagrams
- **Media/**: Images and videos demonstrating the robot's functionality
- **PCB/**: PCB design files
- **STM32CubeIDE Project/**: Source code and project files

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/simulahmed2113/Line-Follower.git
   ```

2. **Open the Project:**
   Launch STM32CubeIDE and open the project located in the `STM32CubeIDE Project` directory.

3. **Build and Flash:**
   Compile the code and flash it onto the STM32F411CE microcontroller.

4. **Hardware Setup:**
   - Assemble the robot components as per the schematics in the `Diagram` directory.
   - Ensure all connections are secure and the LiPo battery is charged.

5. **Operation:**
   - Place the robot on a track with a clear line for it to follow.
   - Power on the robot and observe its line-following behavior.
   - Use the Bluetooth module to control the robot remotely if desired.

## Future Work

- **System Identification:** Utilize MATLAB for system identification to model the robot's dynamics accurately.
- **Advanced Control Systems:** Apply various control strategies to improve the robot's performance and robustness.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License
This project is open-source.


## Acknowledgments

Special thanks to the open-source community and the developers of the tools and libraries used in this project.

