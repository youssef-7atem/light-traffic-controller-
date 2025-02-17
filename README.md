# light-traffic-controller-
The project involves designing a light controller for the intersection of two one-way streets using an FPGA (Cyclone III) and Verilog.
# Traffic Light Controller for the Intersection of Two One-Way Streets

## Project Overview
The **Traffic Light Controller** is an FPGA-based project designed to manage traffic lights at the intersection of two one-way streets. The system ensures safe and efficient traffic flow by controlling the sequencing of green, yellow, and red lights for both streets. The project is implemented using **Verilog** and deployed on an **FPGA (Cyclone III)**, demonstrating the use of state machines and real-time hardware control for traffic management.

## Key Features
- **State Machine Design**: Implements a finite state machine (FSM) to control the traffic light sequences for both streets.
- **Real-Time Control**: Ensures proper timing for green, yellow, and red lights, preventing conflicts between the two streets.
- **FPGA Implementation**: Uses an FPGA to execute the traffic light control logic in real-time, optimizing traffic flow and minimizing congestion.
- **Scalable Design**: The design can be extended to handle more complex intersections or additional traffic scenarios.

## Technologies Used
- **Hardware**: FPGA (Cyclone III)
- **Programming Language**: Verilog (for hardware description)
- **Simulation Tools**: ModelSim (for testing and verification)
- **Development Tools**: Quartus Prime (for FPGA synthesis and implementation)

## How It Works
1. **State Machine Design**: The traffic light controller is modeled as a finite state machine (FSM) with states for each traffic light configuration (e.g., Street A green, Street B red).
2. **Timing Control**: Each state has a predefined duration for green, yellow, and red lights, ensuring smooth transitions between states.
3. **Conflict Prevention**: The FSM ensures that only one street has a green light at any given time, preventing collisions at the intersection.
4. **FPGA Implementation**: The Verilog code is synthesized and uploaded to the FPGA, which executes the traffic light control logic in real-time.
5. **Real-Time Feedback**: The traffic light sequences are displayed on an LED matrix or simulated in a development environment for testing.

## Applications
- **Urban Traffic Management**: Ideal for controlling traffic lights at intersections in urban areas.
- **Smart Cities**: Can be integrated into smart city systems for efficient traffic flow management.
- **Embedded Systems Education**: A great project for learning FPGA programming, Verilog, and state machine design.

## Repository Structure

![image](https://github.com/user-attachments/assets/6e717583-f955-4cd0-9d04-da94a21fc7c6)
first sensor is green while the other red (counting for 30 secs ) 
![WhatsApp Image 2025-02-17 at 20 41 42_5d62f5ab](https://github.com/user-attachments/assets/15f60a01-5613-4137-a41a-97b0bb070de5)
both sensors are in yellow state ( counting for 5 secs)
![WhatsApp Image 2025-02-17 at 20 41 43_1bf6f2f9](https://github.com/user-attachments/assets/8e39db70-9fdb-4919-880c-d9cd458d83fe)
first sensor is red while the other is green ( counting for 30 sec ) 

