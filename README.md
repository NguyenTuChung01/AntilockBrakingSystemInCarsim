# **Antilock Braking System in Carsim**

An anti-lock braking system (ABS) is a safety anti-skid braking system used on aircraft and on land vehicles, such as cars, motorcycles, trucks, and buses. ABS prevents wheel slip from exceeding allowable limits. In this project, I built a controller for the ABS system and simulated it on Carsim.

# Table of contents!

1. [Introduction](#introduction)
2. [Build control system](#buildcontrolsystem)
3. [Controller](#Controller)
4. [Citation](#citation)
5. [Contributing to MOBATSim](#contribution)
6. [Release Notes](#releasenotes)
7. [Getting Started](#gettingstarted)

<a name="introduction"></a>
## Introduction
Antilock braking system is one of the main parts and plays an important role in controlling cars on the road. Is an electronic auxiliary device that prevents the vehicle from skidding under abnormal driving conditions. This system will prevent wheel locking by controlling and varying the oil pressure acting on the brake mechanisms. This project will build On-Off Controller, Fuzzy PID Controller and evaluate their braking efficiency.

Below is the relationship between wheel slip and Adhesion coefficient.
![image](https://user-images.githubusercontent.com/95293469/144709635-7b9a0a8d-cad2-4ddd-b1eb-6449f85887a3.png)
So the goal of the On-Off Controller and the Fuzzy PID Controller is to keep the wheel slip from 0.1 to 0.3.

<a name="buildcontrolsystem"></a>

## Build control system
Build ABS system based on closed loop control system, with desired output is wheel slip with wheel slip equal to 0.15
![image](https://user-images.githubusercontent.com/95293469/144710100-17934251-570b-46ae-aa75-5ae5bd0df354.png)

### Project(CarSim S-Function2)
Multi input is brake wheel cylinder pressure (MPa) at the wheels and multi output is vehicle speed (km/h), wheel speed (km/h) and master cylinder pressure (MPa).
![image](https://user-images.githubusercontent.com/95293469/144745669-6450d5ad-da07-4073-8c26-bd00f2623176.png)
### Actuator(Brake Actuator Model)
The control signal is multiplied by the brake pressure at the master cylinder, transmitted to the Transfer Fcn, then transmitted to and controlled by the brake pressure at each wheel to brake. Transfer Fcn is the transfer function, representing the delay of the hydraulic system when braking or it is the mechanical delay of the solenoid in the brake system.
![image](https://user-images.githubusercontent.com/95293469/144746001-ff5be0ef-927a-4a9b-aa55-dee6b0d980d1.png)
### Caculator Slip
![image](https://user-images.githubusercontent.com/95293469/144746109-61b2056a-cca2-4b8d-8331-6f248b8e25ef.png)

<a name="Controller"></a>

## Controller 
### On-Off Controller
![image](https://user-images.githubusercontent.com/95293469/144746205-cf1caf86-878e-45bd-870d-91217ac2d4d5.png)
### Fuzzy PID Controller
![image](https://user-images.githubusercontent.com/95293469/144746237-6467f5b3-e284-4d48-a513-cae32267cf93.png)
Controller of front wheel
![image](https://user-images.githubusercontent.com/95293469/144746313-87758158-02d0-4404-b6e4-7a0b5220bc60.png)
Controller of rear wheel
![image](https://user-images.githubusercontent.com/95293469/144746360-99e2433e-a500-41b8-a9d2-f14e9e9eec6c.png)


