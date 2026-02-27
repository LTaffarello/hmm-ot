# Discovery of Latent Clinical Phenotypes Through Optimal Transport of Brain Dynamics

![HMM-OT framework](figures/Panel_1_HMM.png)

## Overview
Gaussian Hidden Markov Models (HMM) model resting-state fMRI as transitions among shared latent dynamical states, summarizing each subject as a probability distribution over this latent state space. Optimal Transport (OT) then quantifies the cost of transporting between subjects’ state distributions, yielding a dissimilarity measure that captures temporal information beyond static connectivity.

## Application
Applied to resting-state fMRI from relapsing–remitting multiple sclerosis (RRMS) patients and matched healthy controls to study within-cohort heterogeneity and identify data-driven subgroups.

## Libraries
- Dynamax (Gaussian HMM): https://github.com/probml/dynamax (`from dynamax.hidden_markov_model import GaussianHMM`)
- POT — Python Optimal Transport: https://github.com/PythonOT/POT (`import ot`, e.g. `ot.optim.cg(...)`)
