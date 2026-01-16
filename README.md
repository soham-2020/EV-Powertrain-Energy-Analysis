EV Powertrain Energy Analysis (MATLAB / Simulink)
📌 Project Overview

This project presents a MATLAB/Simulink-based Electric Vehicle (EV) powertrain simulation focused on analyzing battery discharge, State of Charge (SOC), energy consumption, and vehicle speed response under different driving conditions.

An interactive MATLAB App Designer dashboard is integrated with the Simulink model to visualize real-time EV performance and battery behavior.

The project is developed from a core electrical engineering perspective, emphasizing energy flow, motor control, and system-level analysis.
Objectives

Model a complete EV powertrain architecture

Analyze battery discharge and SOC variation

Study the effect of speed demand on energy consumption

Visualize EV performance using a MATLAB App

Demonstrate understanding of electric drives and energy systems
System Architecture

The EV model follows a standard powertrain structure:

Battery → Inverter (PWM) → Motor Drive → Vehicle Dynamics
                          ↑
                   Speed Control Loop

Subsystems Included

Battery model with SOC estimation

PWM-based inverter control

Electric motor drive

Closed-loop speed controller

Vehicle dynamics model
attery & SOC Modeling

Battery State of Charge (SOC) is calculated using current integration:

SOC(t) = SOC(0) − (1 / C) ∫ I(t) dt


SOC is constrained within safe operating limits

Battery voltage, current, and discharge trends are monitored

Energy consumption varies with vehicle speed and load
MATLAB App Designer Dashboard

A MATLAB App Designer interface is used to visualize simulation results.

App Features

Run simulation control

Vehicle speed gauge

Battery SOC gauge (%)

Battery voltage visualization

Real-time monitoring of EV performance

The app helps analyze how driving conditions impact battery discharge and efficiency.
imulation Scenarios

The model supports:

Acceleration

Constant-speed cruising

Load variation

Different speed references

These scenarios are used to evaluate energy demand, SOC depletion rate, and system response.
Tools & Technologies

MATLAB

Simulink

MATLAB App Designer

Electric Drives

Power Electronics

Energy Systems

📊 Key Observations

Higher speed demand leads to increased motor current and faster SOC depletion

Closed-loop control ensures stable speed tracking

Battery discharge behavior closely follows load and speed variations

Visualization improves understanding of energy efficiency trade-offs

🚀 Future Enhancements

Regenerative braking implementation

Advanced battery model with internal resistance

Drive-cycle based analysis (urban / highway)

Hardware-in-the-loop (HIL) integration
