This repository contains the solutions and reports for the Network Dynamics course assignments.

The projects explore various aspects of graph theory, dynamic processes on networks, optimization, and game theory using Python.

***Structure Homework 1***: Centrality & Flow Optimization: 
Analysis of structural properties of graphs and flow dynamics.
Centrality Measures: Implementation of PageRank (iterative power method vs. algebraic solution) and Katz Centrality.
Optimization: Solving Shortest Path problems using Convex Optimization (cvxpy).
Network Flows: Computation of Maximum Flow and analysis of network bottlenecks using Linear Programming.
Graph Layout: Custom visualization of nodes and edges using networkx.

***Structure Homework 2***: Random Walks & Opinion Dynamics:
Simulation of stochastic processes and consensus algorithms.
Continuous-Time Random Walks (CTRW): Simulation of particle movement on a graph.
Comparison between simulated return/hitting times and theoretical predictions based on Markov Chains.
Opinion Dynamics: Implementation of the French-DeGroot model. Analysis of convergence to consensus and the effects of removing edges (breaking strong connectivity) leading to periodic behaviors.
Queueing Networks: Simulation of Open Systems using the Gillespie Algorithm.
Analysis of system stability and identification of bottlenecks in Single-Server configurations.

***Structure Homework 3***: Epidemics & Network Games:
Modeling spreading processes and strategic interactions on complex networks.
SIR Epidemic Model: Simulation of the H1N1 virus spread. Comparison of diffusion on k-Regular vs. Scale-Free (Barabási-Albert) graphs. Analysis of Vaccination Strategies (random immunization) and the "firewall" effect.
Inverse Problem: Fitting model parameters to real empirical data (Sweden 2009 H1N1) using Grid Search.
Small-World Networks: Improving prediction accuracy using the Newman-Watts-Strogatz topology.
Game Theory on Networks: Coordination Games: Dynamics of conformity ($n_1=3$) leading to consensus.
Anti-Coordination Games: Dynamics of rebellion ($n_1=0$) on cyclic graphs (triangles) leading to Geometric Frustration.
Analysis of Best Response vs. Noisy Logit Dynamics and Potentials.

***Technologies & Libraries***
The projects are implemented in Python using the following libraries:
NetworkX: Graph creation and manipulation.
NumPy / SciPy: Matrix operations and linear algebra.
CVXPY: Convex optimization (for flow problems).
Matplotlib: Data visualization and plotting.
