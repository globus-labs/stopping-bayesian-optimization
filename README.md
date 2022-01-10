# Determining when to stop optimizing

This repository contains a series of notebooks used to explore how to know when we should stop running a Bayesian optimization.
As illustrated in [`when-to-stop-optimizing.ipynb`](./when-to-stop-optimizing.ipynb), exactly solving the probability of new experiments improving over 
a target value is intractable for large spaces.
Consequently, much of the work here focuses on creating approximations and - in particular - approximations that can exploit parallel execution.

## Installation

The computational environment is specified in `environment.yml`. Install it using:

```bash
conda env create --file environment.yml --force
```
