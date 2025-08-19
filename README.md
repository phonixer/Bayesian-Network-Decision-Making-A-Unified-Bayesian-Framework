# Bayesian-Network-Decision-Making-A-Unified-Bayesian-Framework
A unified Bayesian Network-based decision-making framework that combines expert intuition and real-world data to evaluate and optimize performance under complex, multi-criteria conditions.

# UAV Swarm Bayesian Framework

This repository implements a unified Bayesian decision-making framework to evaluate and optimize UAV swarm performance by combining expert intuition (AHP) with data-driven methods (SOBOL, BN).

## 📌 Key Features

- Multi-level Bayesian Network model (Goal → Criteria → Factors)
- Integration of AHP weights and real-world data via M-HBNS
- Sensitivity analysis using HBNS
- Adaptive decision-making via real-time BN parameter updating
- Model validation through realistic UAV swarm scenarios

## 🧠 Core Methodology

- **AHP** – Encodes expert judgment into weight vectors.
- **SOBOL** – Captures input-output variance contributions.
- **BN** – Encodes hierarchical relationships, CPTs learned via MAP.
- **HBNS** – Computes sensitivity indices from BN parameters.
- **M-HBNS** – Inverts AHP weights to initialize CPTs.

The code will be released after the paper is accepted


