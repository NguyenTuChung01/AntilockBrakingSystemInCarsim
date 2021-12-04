# **Antilock Braking System in Carsim**

An anti-lock braking system (ABS) is a safety anti-skid braking system used on aircraft and on land vehicles, such as cars, motorcycles, trucks, and buses. ABS prevents wheel slip from exceeding allowable limits. In this project, I built a controller for the ABS system and simulated it on Carsim.

[![Carsim](https://img.shields.io/static/v1?label=Carsim&message=v2017.1&color=96D1AA&logo=github)](https://www.carsim.com/)
[![Contributors](https://img.shields.io/github/contributors/NguyenTuChung01/AntilockBrakingSystemInCarsim)](https://github.com/NguyenTuChung01/AntilockBrakingSystemInCarsim/graphs/contributors)
[![Pull Requests](https://img.shields.io/github/issues-pr-closed/NguyenTuChung01/AntilockBrakingSystemInCarsim?color=g&logoColor=0)](https://github.com/NguyenTuChung01/AntilockBrakingSystemInCarsim/pulls)
[![Commit Activity](https://img.shields.io/github/commit-activity/m/NguyenTuChung01/AntilockBrakingSystemInCarsim)](https://github.com/NguyenTuChung01/AntilockBrakingSystemInCarsim/pulse)

[![stars](https://img.shields.io/github/stars/NguyenTuChung01/AntilockBrakingSystemInCarsim?style=social)](https://github.com/NguyenTuChung01/AntilockBrakingSystemInCarsim/stargazers)
[![forks](https://img.shields.io/github/forks/NguyenTuChung01/AntilockBrakingSystemInCarsim?style=social)](https://github.com/NguyenTuChung01/AntilockBrakingSystemInCarsim/fork)
[![Follow](https://img.shields.io/github/followers/NguyenTuChung01?style=social)](https://github.com/NguyenTuChung01)

# Table of contents!

1. [Introduction](#introduction)
2. [Build control system](#BuildControlSystem)
3. [Requirements](#requirements)
4. [Citation](#citation)
5. [Contributing to MOBATSim](#contribution)
6. [Release Notes](#releasenotes)
7. [Getting Started](#gettingstarted)

<a name="introduction"></a>
## Introduction
Antilock braking system (ABS: Antilock Braking System) is one of the main parts and plays an important role in controlling cars on the road. Is an electronic auxiliary device that prevents the vehicle from skidding under abnormal driving conditions. This system will prevent wheel locking by controlling and varying the oil pressure acting on the brake mechanisms. This project will build On-Off Controller, Fuzzy PID Controller and evaluate their braking efficiency.

Below is the relationship between wheel slip and Adhesion coefficient.
![image](https://user-images.githubusercontent.com/95293469/144709635-7b9a0a8d-cad2-4ddd-b1eb-6449f85887a3.png)
So the goal of the On-Off Controller and the Fuzzy PID Controller is to keep the wheel slip from 0.1 to 0.3.

<a name="#BuildControlSystem"></a>
## Build control system
Build ABS system based on closed loop control system, with desired output is wheel slip with wheel slip equal to 0.15
![image](https://user-images.githubusercontent.com/95293469/144710100-17934251-570b-46ae-aa75-5ae5bd0df354.png)


| Alignment             | Column 2       | Column 3      |   Column 4   |
| --------------------- |:--------------:| -------------:|:-------------|
| Center align column 2 |   căn giữa     |               |              |
| Right align column 3  |                | căn phải      |              |
| Left align numbers:   |                |               |   căn trái   |



