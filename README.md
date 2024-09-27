
# Encore 1.0 Pre-Qualifier Challenge - Buck Converter Design

### Overview

This repository contains the design, simulation, and PCB layout for a **Buck Converter** as part of the Encore 1.0 Pre-qualifier challenge. The objective of this challenge is to design a non-isolated buck converter with:

- **Input Voltage:** 24V (±2% tolerance)
- **Output Voltage:** 5V
- **Max Input Power:** 24W
- **Target Efficiency:** At least 90%

The project showcases the detailed steps of designing, simulating, and demonstrating a functional buck converter, focusing on power conversion efficiency.

### Problem Statement

The task is to design a **DC-DC Buck Converter** capable of converting a 24V input to a 5V output, with a target efficiency of at least 90%. The converter should handle up to **1A of current**, meaning the output power is 5W, and losses are minimized to ensure high efficiency.

The project includes:

1. **Schematic Design:** Created using KiCAD.
2. **Component Selection:** MOSFETs, capacitors, inductors, and switching ICs have been carefully selected based on voltage, current, and wattage ratings.
3. **Simulation:** The circuit has been simulated, and performance parameters such as efficiency and output voltage have been validated.
4. **PCB Layout:** Designed to fit within a **10 cm x 5 cm** form factor with a dual-layer PCB.
5. **Simulation Demonstration:** A video walkthrough explains the design and simulation results, uploaded to YouTube (Link shared below).

### Design Approach

- **MOSFET Selection:** Logic-level MOSFETs were chosen to act as switches based on high-side and low-side configurations. Power MOSFETs are employed to ensure efficient switching with minimal losses.
- **Switching Signal Source:** A 555 timer IC was used to generate the PWM signal required to control the switching operation of the MOSFETs.
- **Capacitor, Inductor, Resistor Ratings:** Each component is selected based on current, voltage, and wattage ratings to ensure the design meets performance and efficiency standards.
  
### Files in the Repository

- **Schematic Design Files:** Located in the `BUCK.kicad_sch` directory.
- **Component Calculations:** Detailed calculations for all components are documented in the `calculations/` folder.
- **Simulation Files:** Contains the KiCAD simulation files (`BuckConverterLT.asc` directory) and output data.
- **PCB Layout:** The PCB layout designed in Altium is available in the `pcb/` folder.
- **Video Demonstration:** A step-by-step explanation of the simulation results has been recorded and uploaded on YouTube.  
  [Video Link](https://youtu.be/VzP02CuskdQ)

### How to Use the Files

1. Clone the repository.
2. Open the KiCAD project files in the respective directories (`BUCK.kicad_sch` and `pcb/`).
3. Run the simulation to observe performance, efficiency, and output voltage characteristics.
4. Review the calculations for component selection to understand the design considerations.

### Team Members

- **Team Leader:** Pranaav Contractor
- **Team Member 1:** Prashant Singh
- **Team Member 2:** Meet Bhesaniya
- **Team Member 3:** Parth Vaghani

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
