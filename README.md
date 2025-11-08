
# Autonomous Mini Vehicle



![C++ Language](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=C%2B%2B&logoColor=white)

#
An Arduino and C++ project for a mini autonomous vehicle. Built on a 2WD chassis, it uses both ultrasonic and infrared sensors for autonomous navigation.

### Goal

The project goal is to develop an autonomous, small-scale vehicle, able to navigate in an unknown environment, avoiding obstacles in real time.

The primary focus is on the integration of sensors and actuators with the microcontroller, applying a reactive control logic.

### Hardware

To develop the project, it was used the following components:

1. **Microcontroller** PIC XXXXX - not a complex project so there is no need for a complex microcontroller
2. **Sensors** ultrasonic XXXX and infrared YYYY - to read the environment.
3. 3.3 V **Battery** - to power the microcontroller.
4. Semiprofessional **PCB** selfmade with cober plate and solution.
5. **Wires** to connect the sensors with microcontroller and microcontroller with motor.
6. XXXXX **Motor** to manipulate the wheels.
7. Bendable metal plates to encapsulate the circuit.

These components where connected as shown in the next eletronic schematic made with XXXXX program. 


The PCBs were designed with EasyEDA resulting in:

### Software

The mini vehicle controller takes as input ultrasonic and infrared reads and decides which direction to move forward. If it is corned, it drives backwards and try moving forward agains, as shown in the following fluxogram.

The sensors reading can be found at X.ino file, the wheel movements are located at Y.ino file and they are integrated at Z.ino file.

### Demonstration
[photos]
[videos]

### Future improvements

Running the mini vehicle with the mentioned circuit, it showed that it's weakness are the fast power discharge of 3.3 battery and wheels. It would be of great improvement to:
1. switch standard wheels for mecanum or omni wheels, so the movement may be more fluid and has less movements to make to get to the destination.
2. adding a stopping point and not relying only on fully discharged batteries.
3. adding rechargeable batteries and light powering plates

