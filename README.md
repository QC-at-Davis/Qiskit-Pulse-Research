# OpenPulse Research

A collection of Jupyter Notebooks experimenting with the OpenPulse framework

## Purpose and Status

OpenPulse was investigated as a potential tool in an ongoing Protein Mapping project but was deemed unsuitable due to its lack of scalability and inability to perform what the organization wanted.

The repository will no longer be active but could potentially be revisited for some future work.

## Launch Environment
Uses the QCaD [Hephaestus](https://github.com/Quantum-Computing-at-Davis/Hephaestus) environment.

Ensure Docker is installed and running in the background, then navigate to directory and run:
```
docker-compose up
```

## Content

* `docker-compose.yml` - Docker Environment file
* `OpenPulse Tutorial.ipynb` - a (heavily) annotated version of the tutorial provided by the Qiskit textbook, designed to fill in any explanatory "gaps" (what is "scheduling" or "qubit acquisition"?)
* `Gaussian Pulse.ipynb` - Understanding how a gaussian pulse is designed/modeled
* `Backend Experimentation.ipynb` - Experimenting with the OpenPulse Backend information