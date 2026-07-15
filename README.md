# Digital MPPT Controller Design & Verification (In Progress)

## Project Overview
This project focuses on the digital design and verification of a solar Maximum Power Point Tracking (MPPT) controller using the Perturb & Observe (P&O) algorithm. The goal is to bridge renewable energy applications with digital system design and robust EDA verification methodologies.

## Target Architecture
* **Core Algorithm:** RTL implementation of P&O control state machine (Verilog).
* **Protocol Interface:** SPI master controller to stream digitized PV sensor data.
* **Verification Environment:** Self-checking testbench with behavioral solar models and Python-based test stimulus.

## Tools & Technologies
* HDL: Verilog
* Simulation: ModelSim / Questa
* Scripting & Math Modeling: Python
