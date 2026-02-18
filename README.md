## Earthquake and Tsunami ODE Simulation

This project is a Python-based simulation of earthquake dynamics, tsunami propagation, and aftershock behavior using ordinary differential equations and numerical integration. The goal is to model key seismic phenomena and visualize how system behavior evolves over time based on physical parameters.

## Overview
The simulation models earthquake motion using a damped harmonic oscillator inspired by elastic rebound theory, simulates aftershock decay using an Omori-style rate equation, and approximates tsunami wave propagation from vertical seafloor displacement. User-defined inputs such as earthquake magnitude, depth, and location are used to generate time-based and spatial visualizations of system behavior.

## Features
- Earthquake displacement and velocity modeling using ODEs
- Aftershock decay simulation inspired by Omori’s Law
- Tsunami wave propagation based on estimated seafloor displacement
- Interactive user input for earthquake parameters
- Visualization of seismic dynamics and tsunami wave height over time and distance

## Technologies Used
- Python  
- NumPy  
- SciPy (`odeint`)  
- Matplotlib  

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/earthquake-tsunami-ode-simulation.git
