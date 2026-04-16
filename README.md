CAN-Based Automotive Dashboard
-------------------------------
Developed a CAN-based automotive dashboard system to simulate real-time communication between multiple Electronic Control Units (ECUs) using the Controller Area Network (CAN) protocol. 
The system demonstrates how modern vehicles exchange data between different modules through a CAN Bus network without a central computer.
The dashboard node receives vehicle data from multiple ECU nodes and displays parameters such as speed, RPM, gear position, and turn indicator status in real time.

 ECU Node Operations 
--------------------
 => ECU Node 1 – Speed & Gear Control
 • Reads speed input using potentiometer
 • Determines current gear position
 • Sends speed and gear data to CAN bus

 => ECU Node 2 – RPM & Indicator Control
 • Simulates engine RPM using potentiometer input
 • Detects left/right indicator status
 • Transmits RPM and indicator data via CAN

 => ECU Node 3 – Dashboard Display Node
 • Receives CAN messages from ECU nodes
 • Decodes CAN IDs and extracts vehicle parameters
 • Displays speed, RPM, gear, and indicator status on CLCD
 • Generates warning alerts for abnormal conditions

 Technologies & Concepts Used 
-----------------------------
 Embedded C Programming
 CAN Communication Protocol
 PIC18F4580 Microcontroller
 Interrupt Handling
 Real-time Data Processing
 Automotive Network Architecture
 Peripheral Interfacing

 Hardware Components 
---------------------
 PIC18F4580 Microcontroller
 CAN Controller
 CAN Transceiver
 CLCD Display
 LM35 Sensor
 Potentiometers (Speed & RPM Simulation)
 Power Supply Module

 Project Outcome 
-----------------
 Gained hands-on experience with embedded firmware, CAN bus communication, and ECU networking
 Implemented multi-node ECU communication using CAN protocol
 Achieved real-time vehicle parameter monitoring
 Simulated automotive dashboard architecture used in modern vehicles

