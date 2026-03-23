# Accretion Disk Simulator (Schwarzschild Spacetime)

# Overview
This project simulates particle motion around a black hole, modeling an accretion disk using numerical solutions of geodesic equations in Schwarzschild spacetime.

The simulation builds on general relativity principles and visualizes how particles behave under strong gravitational fields.

# Features
- Simulation of particle trajectories in curved spacetime
- Accretion disk visualization using multiple particle paths
- Toggle option to enable/disable disk rendering
- Real-time adjustment of black hole mass
- Event-based stopping conditions for realistic orbital decay (ISCO)

# Technologies
- MATLAB
- Numerical Methods (ODE45)
- Scientific Computing & 3D Visualization

# How It Works
The simulation numerically solves the geodesic equations for particles orbiting a black hole.  
Particles are initialized at different radii and angular momenta to form a disk-like structure.

An event condition is used to stop particle motion when it reaches the innermost stable circular orbit (ISCO), creating a more physically accurate model of accretion behavior.

# How to Run
1. Open MATLAB
2. Load or paste the script into a new file
3. Run the program
4. Use controls to toggle the accretion disk and adjust parameters

# Purpose
This project was created to explore astrophysical phenomena through computational modeling and interactive visualization, specifically focusing on black hole environments and accretion dynamics.
