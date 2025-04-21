# Design and Implementation of Instrumentation amplifier
This repository contains the complete design and implementation of an **Instrumentation Amplifier** developed under the **FOSSEE Research Migration Project**, an initiative by IIT Bombay to promote open-source circuit simulation using eSim.
### Project Overview: Design and Implementation of an Instrumentation Amplifier
The Instrumentation Amplifier (IA) is a crucial analog circuit used to amplify low-level signals while rejecting common-mode noise. This project focuses on designing and simulating a three-opamp instrumentation amplifier with high input impedance and low output impedance. The amplifier is designed to ensure accurate amplification of small differential signals, especially in noisy environments, which is essential in applications such as medical instrumentation, sensor signal conditioning, and audio processing.
### Key Objectives of the Project:
#### Design of the Instrumentation Amplifier:
The amplifier is designed using three operational amplifiers (op-amps) in a configuration that maximizes performance by minimizing noise and offset errors. The circuit is carefully designed to ensure that the differential gain is adjustable via external resistors, while the common-mode rejection ratio (CMRR) is optimized.


#### Simulation and Performance Analysis:

The designed amplifier is simulated using open-source EDA tools like eSim, which integrates KiCad and NgSpice for circuit simulation. Performance parameters such as gain accuracy, CMRR, noise reduction, and DC offset are analyzed through simulation results to validate the design.

#### Gain Control and Accuracy:

The project focuses on ensuring precise control over the gain while minimizing distortion or errors in amplification. The adjustable gain feature is verified through simulation by varying external resistances and observing the corresponding changes in the output.


#### Noise Reduction:

The design aims to reduce the inherent noise in the system, especially for low-level signals. This is particularly critical in precision measurements like medical applications (e.g., ECG or EEG) and industrial sensor signal conditioning.

### Tools used 
esim- Opensource EDA tool by FOSSEE, IIT Bombay


## Recognition
Selected  for the FOSSEE Summer Fellowship 2025 at IIT Bombay based on this project to contribute further to the development of open-source EDA tools




