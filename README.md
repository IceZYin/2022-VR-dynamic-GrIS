# 2022-VR-dynamic-GrIS
Scripts and plots for paper Yin et al. (2025) "Improved Understanding of Multicentury Greenland Ice Sheet Response to Strong Warming in the Coupled CESM2-CISM2 With Regional Grid Refinement" published on *Journal of Advances in Modeling Earth Systems*


## Contents

| Directory | Description |
|------------|------------|
| Figure1 | Greenland Ice Sheet and climate model configuration |
| Figure2 | Surface mass balance and melt evolution |
| Figure3 | Spatial patterns of melt and albedo changes |
| Figure4 | Atmospheric circulation and radiation diagnostics |
| Figure5 | Ice sheet response and feedback analysis |
| Supplementary | Scripts used for supplementary figures |


## Data

The analyses use output from coupled CESM2-CISM2 simulations.

The model simulations include:

- Standard 1° CESM2 configuration
- Variable-resolution CESM2 configuration with ~0.25° resolution over the Arctic

Simulation output is stored on NCAR HPC systems and is not included in this repository because of file size limitations.

Users interested in reproducing the analyses should contact the corresponding author.

Preprocessed data used by the plotting scripts are stored in an open repository Zenodo (Herrington & Yin, [2024](https://zenodo.org/records/15049546)).


## Notes

- Raw model output is not distributed through this repository.
- Some scripts contain local file paths that must be modified before execution.
- HPC-specific preprocessing scripts are not included.


## Contact

Ziqi Yin

Department of Atmospheric and Oceanic Sciences

University of Colorado Boulder

Email: ziqi.yin@colorado.edu
