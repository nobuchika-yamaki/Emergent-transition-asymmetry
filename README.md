This repository contains the numerical code used to generate all results reported in the manuscript:

“Physical origins of information: Emergent transition asymmetry and temporal organization in delayed dynamical systems.”

Description

The code implements a minimal stochastic delay-differential system and performs:

numerical integration (Euler–Maruyama),

state-space coarse-graining,

estimation of transition probabilities,

quantification of transition asymmetry,

perturbation and recovery analysis.

No variables corresponding to information, entropy, inference, or optimization are introduced.
All information-like properties are defined operationally and extracted a posteriori from transition statistics.

Usage

Run the analysis with:

python3 methods_reproducible.py


The script automatically generates all transition matrices and summary statistics used in the Results section.

Output files

P_pre.csv, P_post.csv: transition probability matrices

A_pre.csv, A_post.csv: transition asymmetry matrices

summary.csv: global asymmetry and recovery metrics

Requirements

Python 3.x

NumPy

pandas
