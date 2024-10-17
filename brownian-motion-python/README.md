# Brownian Motion Simulation 

This project simulates Brownian motion paths as part of the Stochastic Calculus course I am attending in the context my Master of Financial Engineering at UCLA. The notebook demonstrates how to generate and visualize Brownian paths using Python, which is a foundational concept in financial mathematics, particularly in the modeling of stock prices and option pricing.

## Project Overview

Brownian motion, also known as a Wiener process, is a stochastic process frequently used in financial engineering to model random movements in stock prices. This simulation helps visualize how particles move randomly over time, and demonstrates the theoretical boundaries within which 95.4% of the paths will fall.

The project generates **5000 Brownian paths** and plots them along with the boundaries corresponding to ±2 standard deviations. These boundaries are derived from the properties of the Wiener process and are crucial for understanding risk and variability in financial models.

### Key Features:
- Generates **5000 random Brownian paths** over a time period of 1 unit.
- Plots the paths and overlays **±2 standard deviation boundaries** (±2 * sqrt(t)) to show where 95.4% of the paths are expected to fall.

## Libraries Used
The following Python libraries were used to implement the simulation:
- **numpy**: For numerical operations and random number generation.
- **matplotlib**: For plotting and visualizing the Brownian paths.

## Acknowledgments
This Python-based Brownian motion simulation was inspired by the MATLAB code provided by **Professor Stavros Panageas** as part of the **Stochastic Calculus** course in the Master of Financial Engineering program at UCLA.

The original MATLAB code was used to simulate Brownian paths, and this project is a Python implementation of the same concept.

You can install these libraries using the following command:
```bash
pip install numpy matplotlib

