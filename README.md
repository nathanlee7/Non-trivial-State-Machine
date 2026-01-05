# Non-trivial-State-Machine
Created a physical free state machine through circuitry and programmed functionality using SystemVerilog

Finite State Machine (FSM) – SystemVerilog
Overview

This project implements a multi-state finite state machine (FSM) written in SystemVerilog, verified through simulation and validated on physical hardware. The design was developed following a full hardware workflow, from schematic design in KiCad to breadboard prototyping and final FPGA implementation.

Functionality

Synchronous FSM with multiple defined states

Deterministic state transitions based on digital inputs

Outputs reflect the current FSM state (Moore-style design)

Reset returns the system to a known safe state

Design & Verification

FSM logic written in synthesizable SystemVerilog

Verified using a custom testbench

Hardware behavior confirmed using LEDs and physical inputs

FPGA behavior matched simulation results

Hardware Implementation

Logic first modeled in KiCad

Circuit prototyped on a breadboard

Final design deployed to an FPGA

Repository Structure
rtl/           → SystemVerilog modules  
sim/           → Testbench and simulation files  
hardware/      → KiCad schematics  
constraints/   → FPGA pin constraints  
docs/          → State diagrams and images  

Tools

SystemVerilog

KiCad

FPGA synthesis & simulation tools

Author

Nathan Lee
