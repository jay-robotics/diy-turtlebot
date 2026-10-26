# diy-turtlebot

# DIY Differential Drive Robot

A physical differential drive mobile robot I built from scratch, based on the open-source [TortoiseBot](https://rigbetellabs.com/tortoisebot) design by RigBetel Labs. It uses a Raspberry Pi 4 and a 360° 2D LiDAR, and runs ROS 2.

## Photos

<p align="center">
  <img width="18%" alt="front" src="https://github.com/user-attachments/assets/af74a811-5fc8-496f-8e4e-a2a0e28bcad0" />
  <img width="18%" alt="side" src="https://github.com/user-attachments/assets/b89b84fe-370c-4311-8541-b0b16f54ac22" />
  <img width="18%" alt="side2" src="https://github.com/user-attachments/assets/9694ad78-e866-4807-b734-111e5fe8ed54" />
  <img width="18%" alt="back" src="https://github.com/user-attachments/assets/4f439928-50c0-4767-a224-44b347462360" />
  <img width="18%" alt="above" src="https://github.com/user-attachments/assets/d60ee4f6-c0de-446b-9f55-3a549678e082" />
</p>

## Hardware

| Part | Details |
|------|---------|
| Computer | Raspberry Pi 4 Model B |
| Sensor | 360° 2D LiDAR |
| Camera | Raspberry Pi camera (CSI) |
| Motors | 2x geared DC (BO) motors with wheels |
| Motor driver | L298N |
| Power | 11.1V 3S Li-ion battery pack, battery monitor module, power distribution module |
| Chassis | Multi-layer plates with spacers, caster wheel |

## What I did
- Assembled the multi-layer chassis, motors, caster wheel and mounting plates
- Wired the power distribution, motor driver, LiDAR and camera to the Raspberry Pi
- Ran ROS 2 on the robot

## Software
My autonomous exploration code for this kind of robot: [ros2-random-exploration](https://github.com/jay-robotics/ros2-random-exploration)

## Credits
Design by [RigBetel Labs](https://rigbetellabs.com).
