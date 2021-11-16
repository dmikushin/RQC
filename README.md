# Simulating Random Quantum Circuit with PEPS

This repo presents the Python code used for the simulations in our [paper](1905.08394.pdf).

## Introduction

Simulating Random Circuit Sampling using Projected Entangled Pair States (PEPS):

* The performance of matrix product states is much less effective if the underlying quantum system is essentially two-dimensional.
* The Projected Entangled-Pair States (PEPS) is a tensor-network quantum states representation designed for two-dimensional lattices.

Our PEPS-based simulator is a general-purpose quantum circuit simulator for arbitrary quantum circuits:

* Stores the full quantum state
* Can be used to compute single amplitudes, observables, and also perform sequences of quantum measurements.

## Usage

```
python3 -m venv ./venv
source ./venv/bin/activate
pip3 install numpy scipy
python3 ./randomquantumcircuit.py
```

