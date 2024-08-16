### Overview ###

This repository is associated with the manuscript "The physical chemistry of interphase loop extrusion" and houses notebooks demonstrating the lattice and polymer implementations of the five-state model of interphase cohesin.


Preprint available here: ** link coming soon **



Code in this repository relies on:
- https://github.com/open2c/polychrom-hoomd/ for 3D polymer simulations implemented with [HooMD-Blue](https://github.com/glotzerlab/hoomd-blue)
- https://github.com/Fudenberg-Research-Group/discrete-time-extrusion for 1D lattice models of extrusion implemented in Python
- [SymPy](https://www.sympy.org/en/index.html) for fitting ODE models

To simulate genome conformations, we couple a 1D lattice model describing cohesin dynamics with a 3D polymer model:
![Model](./figures/five-state-polymer.png?raw=true))



![Movie]((https://github.com/Fudenberg-Research-Group/five_state_cohesin/tree/figs/figures/anim_loop.mp4)
