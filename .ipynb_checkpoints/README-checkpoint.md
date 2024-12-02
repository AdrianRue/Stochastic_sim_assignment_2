# Stochastic_sim_assignment_2

## Overview
We simulate the following scenarios:

- M/M/1 vs. M/M/n: Comparing single-server and multi-server systems to examine how adding servers affects waiting times.
- FIFO vs. SJF Scheduling: Analyzing different job scheduling strategies under identical conditions.
- M/D/n vs. M/H₂/n: Evaluating the impact of deterministic versus hyper exponential service times on system performance.

## Objectives

The primary goals of the simulations are:

- To validate queueing theory predictions for average waiting times in M/M/1 and M/M/n systems.
- To assess the performance differences between FIFO and SJF scheduling strategies.
- To evaluate how deterministic (M/D/n) and hyperexponential (M/H₂/n) service times affect key performance metrics.
- To understand the influence of traffic intensity ($\rho$) on system behaviour.
- 
## Requirements

The project requires the following Python packages:

- `Simpy`
- `numpy`
- `matplotlib`
- `scipy`
- `random`