# Comparing interatomic potentials for dislocations in fcc Ni

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TheNewPing/multi_scale_md_tutorial/blob/master/ni_dislocation_benchmark.ipynb)

A hands-on tutorial on how to test an interatomic potential for dislocation simulations, using fcc Ni as the example.
The notebook goes from basic properties (lattice parameter, elastic constants, stacking-fault energies) to an edge
dislocation: how it splits into two Shockley partials, the stress needed to move it (CRSS), and its disregistry.
All simulations run with LAMMPS through its Python interface.

## Running it

The tutorial is meant to run on [Google Colab](https://colab.research.google.com/): click the button above.
You only need a browser and a Google account.
the LAMMPS scripts and potential files from this repository.

## Contents

| | |
|---|---|
| `ni_dislocation_benchmark.ipynb` | the tutorial notebook |
| `scripts/` | the LAMMPS input scripts used by the notebook |
| `ni_potentials/` | the EAM potential files (Mishin et al. 2002 and 2004) |
