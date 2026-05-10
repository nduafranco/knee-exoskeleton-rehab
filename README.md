
# Smart Rehabilitation Knee Brace: Motorized Ball Screw Actuator

## Project Overview
This project was developed at JKUAT to evaluate three distinct linear actuation systems for an active-assist knee exoskeleton. I led the development and simulation of **Concept 3: The Motorized Ball Screw System**, focusing on transforming the device from a passive brace into an active rehabilitation platform.

## Concept 3 Design Specifications
The design prioritizes high torque density and mechanical precision to assist with post-operative recovery and gait synchronization.

**Actuation:** NEMA 34 high-torque stepper motor.

**Transmission:** SFU1204 precision ball screw (90% efficiency).

**Frame Material:** Aluminum 6061-T6.
* **Resolution:** 20-micron control precision (0.02 mm/step).

## Engineering Validation & FEA
I conducted structural and motion simulations to verify the system's performance under biomechanical loads.

* **Torque Demand:** Inverse dynamics identified a 33 Nm peak demand during the gait cycle.
* **Force Capacity:** The actuator sustains a 5,040 N design threshold with a 325% torque reserve.
* **Structural Integrity:** * **Max Stress:** 136.53 MPa under peak stall torque.
    * **Safety Factor:** 2.01.
    * **Mechanical Precision:** Displacement limited to < 1.5 mm to maintain axial alignment.

## Key Contributions
* **Mechanical Design:** Modeled the full assembly, including the polycentric joint linkages and actuator mounting, in Autodesk.
* **Simulation & Kinematics:** Performed inverse dynamics using clinical gait data in Simscape Multibody to establish hardware baselines.
* **Technical Reporting:** Authored comprehensive design documentation and performance analysis using LaTeX.
