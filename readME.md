# Conway's Game of Life — Cellular Automata Simulation

This repository contains an implementation of **Conway’s Game of Life**, a zero-player cellular automaton that demonstrates how complex global behavior can emerge from simple local rules.

The project simulates the evolution of a 2D grid of cells over discrete time steps and visualizes pattern formation, stability, oscillation, and self-organization.

---

## Overview

**Conway’s Game of Life**, introduced by mathematician John Conway, is a cellular automaton where each cell evolves according to deterministic rules based solely on its neighboring cells.

Each cell exists in one of two states:

- Alive (1)
- Dead (0)

The grid evolves iteratively across generations.

---

## Rules of the Game

At every time step, the following rules are applied simultaneously to all cells:

1. **Underpopulation**  
   A live cell with fewer than 2 live neighbors dies.

2. **Survival**  
   A live cell with 2 or 3 live neighbors survives.

3. **Overpopulation**  
   A live cell with more than 3 live neighbors dies.

4. **Reproduction**  
   A dead cell with exactly 3 live neighbors becomes alive.

Neighborhoods are computed using the **8 surrounding cells** (Moore neighborhood).

---

## Features

- Grid-based cellular automaton simulation
- Iterative generation updates
- Visualization of evolving patterns
- Emergent behavior demonstration
- Customizable grid size and initialization
- Educational implementation using NumPy and visualization tools

---
## Requirements

- Python 3.9+
- numpy
- matplotlib
- Jupyter Notebook

Install dependencies:

```bash
pip install numpy matplotlib jupyter
```

## Running the Simulation

Start Jupyter:
```bash
jupyter notebook
```
Open the notebook:
```bash
Conway_Game_of_Life.ipynb
```
Run all cells to start the simulation and visualize grid evolution.

Alternatively, launch directly:
```bash
jupyter notebook Conway_Game_of_Life.ipynb
```
## Concepts Demonstrated

Cellular automata

Emergent complexity

Discrete dynamical systems

Local rule–based evolution

Pattern stability and oscillation

Common observable structures include:

Still lifes

Oscillators

Moving patterns (e.g., gliders)

## Educational Purpose

This project serves as a compact demonstration of how simple deterministic rules can generate complex and unpredictable macroscopic behavior — a foundational idea in complexity science and computational modeling.
