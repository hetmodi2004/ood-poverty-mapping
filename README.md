# OOD Generalisation for Poverty Mapping

## Overview

This project investigates out-of-distribution (OOD) generalisation
for poverty mapping using satellite imagery.

The task is to predict continuous asset wealth while evaluating
generalisation across geographic domains and urban/rural subgroups.

## Dataset

PovertyMap-WILDS benchmark.

The project uses multispectral satellite imagery together with
nighttime-light information.

## Objective

The main objective is to investigate how models perform when
evaluated on geographic domains that differ from the training data.

## Methodology

The project investigates:

- Empirical Risk Minimization (ERM)
- Group Distributionally Robust Optimization (Group DRO)
- Invariant Risk Minimization (IRM)
- Domain-Adversarial Neural Networks (DANN)

## Evaluation

Models are evaluated using:

- Pearson correlation
- Worst-group Pearson correlation
- Mean Squared Error (MSE)

Additional analysis includes country-level and urban/rural
error analysis.

## Repository Structure

```text
notebooks/    Jupyter notebooks
results/      Evaluation and EDA outputs
models/       Information about trained models
