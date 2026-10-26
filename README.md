# DIY Differential Drive Robot

A differential drive mobile robot I built myself. I chose and bought the components, soldered and wired the electronics, assembled the chassis, and wrote the software. It runs on a Raspberry Pi 4 with a 360° 2D LiDAR and ROS 2.

## Photos

<p align="center">
  <img width="70%" alt="front" src="https://github.com/user-attachments/assets/af74a811-5fc8-496f-8e4e-a2a0e28bcad0" />
  <img width="70%" alt="side" src="https://github.com/user-attachments/assets/b89b84fe-370c-4311-8541-b0b16f54ac22" />
  <img width="70%" alt="side2" src="https://github.com/user-attachments/assets/9694ad78-e866-4807-b734-111e5fe8ed54" />
</p>
<p align="center">
  <img width="70%" alt="back" src="https://github.com/user-attachments/assets/4f439928-50c0-4767-a224-44b347462360" />
  <img width="70%" alt="above" src="https://github.com/user-attachments/assets/d60ee4f6-c0de-446b-9f55-3a549678e082" />
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
- **Sourcing:** Selected and bought all components myself
- **Electronics:** Soldered connections and wired the power distribution, motor driver, LiDAR and camera to the Raspberry Pi
- **Mechanical:** Assembled the multi-layer chassis with motors, caster wheel and mounting plates
- **Software:** Wrote [describe: motor control, LiDAR setup, ROS 2 nodes, etc.]

## Challenges
- [One real problem you hit, e.g. motors spinning the wrong way, power drops, LiDAR not detected, and how you fixed it]

## Software
My autonomous exploration code for this kind of robot: [ros2-random-exploration](https://github.com/jay-robotics/ros2-random-exploration)

## Credits
The overall layout was inspired by the open-source [TortoiseBot](https://rigbetellabs.com/tortoisebot) by RigBetel Labs.
