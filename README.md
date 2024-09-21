# Moore FSM-Based Traffic Light Controller | Verilog HDL | Xilinx Vivado

[**Click here to view the project report**](https://github.com/bipriti/Moore_FSM_Based_Traffic-Light-Controller_VerilogHDL/blob/main/Moore%20FSM%20based%20Traffic%20Light%20Controller_%20Verilog%20HDL.pdf)

### Project Overview
This project implements a **Moore Finite State Machine (FSM)** for a traffic light controller using **Verilog HDL**. The design manages traffic flow at an intersection by controlling traffic lights for multiple roads based on vehicle detection and timed transitions. The system is verified through simulation using **Xilinx Vivado**.

### Key Features
- **FSM Design**: Based on the **Moore model**, where outputs are determined solely by the current state, ensuring predictable control.
- **Sensor Integration**: Inputs from vehicle detection sensors (`Sa`, `Sb`) help dynamically control the traffic lights for efficiency.
- **Timing & Control**: Synchronized using a **positive edge-triggered clock** to ensure accurate state transitions.
- **Asynchronous Active-Low Reset**: Allows for immediate system reset to a safe state, regardless of the clock signal.
- **Simulation Results**: Detailed simulation was performed using **Xilinx Vivado**, and the state transitions and light controls were validated using waveform analysis.

### Application
This project is based on a **real-life traffic control system** at intersections, demonstrating the implementation of **Verilog HDL** in managing vehicle flow effectively. The FSM-driven design adapts to real-time traffic conditions through vehicle detection sensors, controlling the timing of traffic lights to optimize flow and reduce congestion.

The **Verilog HDL** implementation in this project showcases how digital hardware design techniques can be applied in real-world systems, making traffic control smarter and more responsive.

### Tools Used
- **Verilog HDL**: Hardware description language for FSM implementation.
- **Xilinx Vivado**: Design and simulation tool for functional verification.
  
### Project Files
[**Click here to view the project report**](https://github.com/bipriti/Moore_FSM_Based_Traffic-Light-Controller_VerilogHDL/blob/main/MooreFSM_DesignCode.v)
