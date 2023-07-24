SIMULATING QUANTUM MANY-BODY DYNAMICS ON DIGITAL QUANTUM COMPUTERS
===================================================================

This repository contains a recreation of the work from "Simulating quantum many-body dynamics on a current digital quantum computer". The project leverages quantum circuits to simulate the dynamics of quantum many-body systems, providing both trotterized and exact diagonalization approaches.
(Original work: https://www.nature.com/articles/s41534-019-0217-0)

********

DESCRIPTION
===========

Quantum Many-Body Systems are at the heart of quantum mechanics and solid-state physics. Their behavior, especially over time, is of great interest to both theorists and experimentalists. The project aims to understand these dynamics by simulating them on a quantum computer. This repository contains:

- Trotterized quantum circuits which simulate the time evolution of the quantum system.
- Exact diagonalization approaches for the direct comparison of results from quantum circuits.
- Analysis tools for understanding local magnetizations, spin correlations, and more.

FEATURES
========

- Trotterized Simulation: This approach breaks down the time evolution operator into manageable chunks, allowing for efficient simulation on current noisy intermediate-scale quantum computers (NISQ).
- Exact Diagonalization: A non-quantum method to find the exact time evolution of the system, allowing for a benchmark comparison with the trotterized approach.
- Visualization: Tools for visualizing the time evolution of various physical quantities like local magnetizations and spin correlations.
