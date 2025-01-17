Here's the updated version of the README with the clarification included:

---

# Dynamics_exam_public

Project for the final examination of the course *Dynamics of Stellar Systems* (2023-2024), taught by Professor Massimo Dotti at Università degli Studi di Milano-Bicocca.

---

## Overview

This project focuses on analyzing the dynamics of a galactic disk embedded within a dark matter halo. The system is modeled as a Miyamoto-Nagai disk of particles within a static Hernquist potential. 

The study includes:
1. Examining a stable configuration against perturbations to analyze the system's equilibrium.
2. Introducing perturbations to observe the formation of a galactic bar.

Key goals:
- Initialize particle positions and velocities for equilibrium configuration. One script provides the equilibrium initialization, while another sets up a less stable configuration to induce bar formation.
- Analyze the equilibrium state of the disk.
- Investigate bar formation through Fourier decomposition, quantifying its strength and extent.

---

## Repository Contents

This repository includes scripts and tools for:
- **Initialization**: Generating particle positions and velocities for equilibrium and non-equilibrium configurations. (  , )
- **Equilibrium Analysis**: Analyzing the stable configuration of the galactic disk. ()
- **Bar Analysis**: Investigating bar formation through Fourier decomposition, quantifying its strength and length. ()

**Note**: Full simulation data files are hosted externally due to size constraints. Access them via this [Google Drive folder](https://drive.google.com/drive/folders/1HyY4uvtq2BRBCbJIa6yHzu842k-u3KG8?usp=sharing).

---

## Simulation Framework

The simulations were carried out using a customized version of a treecode. The main function was adapted to include a static Hernquist potential, ensuring consistency with the system setup. For details about the treecode, refer to the [Treecode Documentation](https://legacy.ifa.hawaii.edu/faculty/barnes/treecode/treeguide.html).  

---

## Acknowledgments

Special thanks to [Ludovica Carbone](https://github.com/ludovicarbone) for her collaboration and contributions to the initialization stage.  

--- 

Let me know if further refinements are needed!
