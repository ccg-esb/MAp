# MAp: Mutation Accumulation in Plasmids

## Overview
This repository contains a computational framework for simulating mutation accumulation experiments in bacterial populations harboring multicopy plasmids. The model simulates the behavior of plasmids across multiple bacterial generations, incorporating critical biological processes such as plasmid replication, segregation, and random mutation events. The primary objective is to quantify the balance between mutation probability, which increases with higher plasmid copy number (PCN), and segregational drift, which clears mutations more effectively at high PCN.

## Jupyter Notebooks

### 1. [py_MAp_1_model.ipynb](https://github.com/ccg-esb/MAp/blob/main/py_MAp_1_model.ipynb)
This notebook contains the core model implementation and examples. It uses Object-Oriented Programming (OOP) to represent plasmids, bacterial cells, and populations.

#### Contents:
- **Model Overview:** Explanation of the computational model.
- **Plasmid Class:** Manages properties and mutations of individual plasmids.
- **Bacteria Class:** Represents bacterial cells containing plasmids.
- **Population Class:** Simulates a collection of bacterial cells over multiple generations.
- **Examples:** Demonstrations of how to use the model classes.

### 2. [py_MAp_2_experiment.ipynb](https://github.com/ccg-esb/MAp/blob/main/py_MAp_2-experiment.ipynb)
This notebook runs the simulations, storing results in PKL files for later analysis. It allows for multiple simulation runs with varying parameters to study plasmid dynamics under different conditions.

#### Contents:
- **Simulation Setup:** Definition of parameters such as mutation rates, plasmid copy numbers, and the number of generations.
- **Running Simulations:** Execution of multiple simulation runs and storage of results.
- **Data Storage:** Saving simulation results in PKL files for future analysis.

### 3. [py_MAp_3_analysis.ipynb](https://github.com/ccg-esb/MAp/blob/main/py-MAp_3-analysis.ipynb)
This notebook loads the simulation results and performs detailed analysis and visualization. It helps interpret the data and provides insights into plasmid dynamics.

#### Contents:
- **Data Loading:** Loading simulation results from PKL files.
- **Analysis Functions:** Functions to calculate mutation statistics and dynamics.
- **Visualization:** Plotting mutation accumulation, dynamics, and probabilities.
- **Empirical Comparison:** Comparing simulation results with empirical data.

