# Dynamics_exam_public

Project for the final examination of the course *Dynamics of Stellar Systems* (2023-2024), taught by Professor Massimo Dotti at Università degli Studi di Milano-Bicocca.

---

## Overview

This project focuses on analyzing the dynamics of a galactic disk embedded within a dark matter halo. The system is modeled as a Miyamoto-Nagai disk of particles within a static Hernquist potential. 

The study includes:
1. Examining a stable configuration against perturbations to analyze the system's equilibrium.
2. Introducing perturbations to observe the formation of a galactic bar.

---

## Repository Contents

This repository includes scripts and tools for:
- **Initialization**: Generating particle positions and velocities for equilibrium and non-equilibrium configurations. (Initialization_equilibrium.ipynb, Initilaization_oo7.ipynb)
- **Equilibrium Analysis**: Analyzing the stable configuration of the galactic disk. (visualization_equilibrium.ipynb)
- **Bar Analysis**: Investigating bar formation through Fourier decomposition, quantifying its strength and length. (visualization_007.ipynb)

**Note**: Full simulation data files are hosted externally due to size constraints. Access them via this [Google Drive folder](https://drive.google.com/drive/folders/1h83yOWRyBt--1jPrWqwf4KBBv79bfWXi?usp=sharing).

---

## Simulation Framework

The simulations were carried out using a customized version of a treecode. The main function was adapted to include a static Hernquist potential, ensuring consistency with the system setup. For details about the treecode, refer to the [Treecode Documentation](https://legacy.ifa.hawaii.edu/faculty/barnes/treecode/treeguide.html).  

---

## Acknowledgments

Special thanks to [Ludovica Carbone]((https://github.com/ludovicarbone)) for her collaboration and contributions to the initialization stage.  


