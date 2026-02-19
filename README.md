# Earthquake and Tsunami ODE Simulation

This project presents a Python-based simulation of earthquake dynamics, tsunami propagation, and aftershock behavior using ordinary differential equations (ODEs) and numerical integration. The goal is to explore how simplified physical models can capture qualitative seismic behavior and how system responses evolve over time based on user-defined parameters.

---

## Overview

The simulation models:
- **Earthquake motion** using a damped harmonic oscillator inspired by elastic rebound theory
- **Aftershock activity** using an Omori-style rate equation
- **Tsunami propagation** using a simplified wave response driven by estimated vertical seafloor displacement

Users specify parameters such as earthquake magnitude, depth, location, and simulation duration. The system then generates time-domain and spatial visualizations illustrating earthquake motion, aftershock trends, and tsunami wave behavior.

This project emphasizes **conceptual modeling and visualization**, not predictive accuracy.

---

## Features

- Earthquake displacement and velocity modeling using ODEs  
- Aftershock decay dynamics inspired by Omori’s Law  
- Tsunami wave propagation based on estimated seafloor displacement  
- Interactive user input for seismic parameters  
- Clear visualizations of time-domain and distance-based behavior  

---

## Simulation Results

### Earthquake Dynamics
The plots below show earthquake displacement, velocity, and aftershock activity over time.

<img width="1255" height="789" alt="earthquake_dynamics" src="https://github.com/user-attachments/assets/d19ba34f-6181-4e83-8abc-f26f144d0d3e" />

---

### Tsunami Propagation
This figure visualizes tsunami wave height as a function of distance from the epicenter at multiple time snapshots.

<img width="1300" height="940" alt="tsunami_propagation" src="https://github.com/user-attachments/assets/8ba833fd-c062-403b-a309-8f675ee05550" />

---

## Technologies Used

- Python  
- NumPy  
- SciPy (`odeint`)  
- Matplotlib  

---

## How to Run (Recommended)

### Option 1: Run in Google Colab (No Setup Required)

Open and run the notebook directly in Google Colab:

➡️ **[Open in Google Colab](https://colab.research.google.com/github/JacksonBopp/earthquake-tsunami-ode-simulation/blob/main/Earthquake_ODE.ipynb)**

---

### Option 2: Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/JacksonBopp/earthquake-tsunami-ode-simulation.git
   cd earthquake-tsunami-ode-simulation
