# CHEM 274A - Lab 2
September 13, 2022

Today, we will be focusing on Molecular Dynamics (MD) Simulations of Alkanes using [OpenMM](https://openmm.org/documentation).

---

## Questions
- How do I run a simulation?
- How do I analyze a simulation?

## Objectives
- Understand the steps for running a simulation.
- Be able to perform analysis on properties such as bond length, angles, and torsions.
- Understand a PMF calculation.

---

## Setup
1. Clone this repo!
2. Create a `conda` environment with the needed software using the `conda-env.yaml`. This will install OpenMM and all the software you need for this lab in an environment called `mm-tools`.

```bash
conda env create -f conda-env.yaml
conda activate mm-tools
```

3. Read the first two sections of the [Introduction](https://education.molssi.org/mm-tools/01-introduction/index.html) to this activity from The Molecular Sciences Software Institute.

---

## Exercise
Use the notebook `openmm_sims.ipynb` to run molecular dynamics simulations. Follow the instructions in the notebook.