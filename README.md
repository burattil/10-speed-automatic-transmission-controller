# 10-Speed Automatic Transmission Controller

## Project Overview
This project was completed as part of the EcoCAR Innovation Challenge's Propulsion Controls & Modelling sub-team development challenge at McMaster University. 

The objective was to develop a controller for a simulated 10-speed automatic transmission using MATLAB/Simulink and Stateflow. The controller determines gear selection and manages transmission operating states based on vehicle conditions and simulated inputs, while satisfying safety, performance, and drivability requirements. 

The vehicle plant and simulation model were provided as part of the challenge. This project solely focused on the development of the transmission controller, defining requirements, and verifying its functionality.

## My Contributions
- Developed transmission control logic to manage gear selection and transitions between Park, Reverse, Neutral, and Drive states.
- Implemented gear-shifting logic for a 10-speed automatic transmission based on vehicle operating conditions and driver inputs.
- Incorporated safety constraints to prevent invalid gear selections and maintain engine operation within specified RPM limits.
- Developed requirements to define expected controller behaviour.
- Created a test suite in Simulink Test to evaluate controller functionality under various driving conditions.
- Investigated controller performance against vehicle acceleration and drivability requirements.

## Controller Functionality 
The controller receives inputs from the vehicle model (various different combinations of speed, throttle, brake, driver gear-selection, etc.) and determines the appropriate transmission behaviour. 

Key functionality includes:
- Gear selection and transitions between transmission operating states.
- Engine speed monitoring and gear selection constraints.
- Parking brake actuation and associated safety interlocks.
- Protection against invalid gear selections based on vehicle speed.
- Transmission response under different driving conditions.

## Requirements & Verifications 
Systems requirements were developed and documented using MATLAB Requirements Toolbox.

Controller functionality was evaluated using MATLAB Simulink Test with many different simulated inputs, with test cases covering operating-state transitions, gear selection, and safety constraints.

The challenge also included a vehicle acceleration target of 0–60 mph in under 12 seconds. In this model, 60 mph mark was hit at 11.8 seconds.

## Technologies Used
- MATLAB
- Simulink
- Stateflow
- Simulink Test
- MATLAB Requirements Toolbox
- Git / GitHub

## Acknowledgements
This project was completed using the development challenge framework and vehicle simulation model provided by the EcoCAR Propulsion Controls & Modelling sub-team. 

The original repository can be found here: 

[EcoCAR PCM Dev-Challenge Repository](https://github.com/sticklat/PCM-Dev-Challenge_EIC-Y1)

## Author
Luca Burattini
