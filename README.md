# Simulation Files: Cyclic Loading of Wood Cell Wall Structures

This repository contains input files, representative output data, and atomic configurations used in the molecular dynamics study titled:

**"Microfibril Angle and Moisture Synergistically Govern Fatigue Resistance in Wood Nanocomposites"**

## 📂 File Overview

| File / Folder | Description |
|---------------|-------------|
| `1-Equilibration.in` | LAMMPS input script for system equilibration |
| `1-Equilibration.100000000` | LAMMPS  output after equilibration |
| `Relaxation.data` | Initial data file defining the atomistic structure (CNF–HEMI-WATER composite) |
| `2-LoadC1.in` | Input script for first-stage cyclic loading |
| `2-ave_stressofall.dat` | Output: averaged stress–strain data (stage 1) |
| `C1-dump-Strain0.15.3000000` | Dump file at strain = 0.15 (frame 3,000,000) |
| `3-LoadC2.in` | Input script for second-stage loading |
| `3-ave_stressofall.dat` | Output: averaged stress–strain data (stage 2) |
| `C2-dump-Strain0.175.1800000` | Dump file at strain = 0.175 (frame 1,800,000) |
| `1-dump.0` | Initial atomic dump (frame 0) |

> The prefix numbers indicate the simulation stage:  
> `1-` Equilibration → `2-` First loading cycle → `3-` Loading extension

## ⚙️ Software Requirements

- **LAMMPS version**: 29Oct2020 or later
- Simulation units: real  
- Boundary conditions: periodic in all directions (P P P)

## 📈 Data Use Notes

- `*.in` files can be run directly with LAMMPS


