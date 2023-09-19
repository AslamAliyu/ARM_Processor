# ARM_Processor
 The ML Autonomous Car project is sponsored by Lockheed Martin and is intended as hands-on exploration of AI/ML concepts.

# Abstract

ECD304 ML Autonomous Car is an ECD project for the  2022-2023 school year sponsored by Lockheed Martin. The project is designed to explore machine learning concepts by implementing a ML autonomous car based on an open-source platform. The goal of this project is to design a car that can maneuver autonomously around a track using a driving model, developed through use of a ML neural network, that makes steering decisions based on visual track data. In addition, in order for the car to be more efficient, variable throttle will be introduced allowing the car to make speed decisions depending on where it is along the track. Additional stretch goals of object detection and stop sign detection were set, but were not attempted due to time constraints. For the first stage of the project, three open-source platforms were evaluated to construct the car: the NVIDIA JetRacer, the DeepPiCar and the DonkeyCar. Once the NVIDIA JetRacer was selected as the ideal open-source platform for the project and requirements were defined, a design was developed and implemented, centered around the Jetson Nano Developer’s Kit. Autonomous driving models were developed using collected camera images and steering directions processed through a ML neural network. These models were refined in live training and autonomous driving tests. A working autonomous driving model was developed that allowed for constant throttle and variable throttle control within the bounds of the track through multiple laps. The car had an average lap time of ~8.5 seconds for constant throttle control and ~8.3 seconds for variable throttle control–fulfilling the sponsor's requirements.

# Technical Review

To design an ML autonomous car, the balance of hardware and software are key. The microcontroller is the brain of the system. It processes input data from the sensors and sends instructions to the steering and motor components to control the car. The autonomy operation comes from the software design. The code defines the operation of all on-board components. It defines the parameters for the autonomous driving model, and how that model is executed while driving.

<img width="584" alt="Screenshot 2023-09-19 at 9 00 40 AM" 
 src="https://github.com/AslamAliyu/ARM_Processor/assets/70922558/fd22e3f1-b3f0-4cf5-b8fa-1df52abded73">

 
