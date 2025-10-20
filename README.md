# Cellular Automata GPU Implementation

## Project Description

This project was developed as the final work for the course [Introduction to HPC Programming in Python](https://ig.conae.unc.edu.ar/introduccion-a-la-programacion-hpc-2025/), offered by the Instituto Gulich in September 2025. It focuses on implementing a Cellular Automata (CA) model for wildfire simulation on GPUs. The implementation is based on the [Julius Wons’ project](https://github.com/jcwons/Wildfire-Mapping-and-Simulation-with-Cellular-Automaton). To evaluate performance gains, the project compares parallelized GPU execution time with the sequential approach.

The developed code includes the CA implementation using PyCUDA, tested with both toy data and real Sentinel-2 imagery from the Paraná River Delta (Argentina). It also contains scripts and visualizations demonstrating the computational speedup achieved through GPU parallelization compared to sequential processing.

## Repository Description

* **Notebooks:** Contains the CA implementation on GPUs using toy and real data, along with performance assessment visualizations.

**NOTE:** Notebooks can be runned on Google Colabs notebooks which offers GPUs using, altough with certain limitations. 
* **Data:** Sentinel-2 imagery from the Paraná River Delta (Argentina), acquired between July and September 2020.  
* **Results_visz:** Includes an animation of the GPU implementation results on the S2 data and visualizations of computation time improvements.
