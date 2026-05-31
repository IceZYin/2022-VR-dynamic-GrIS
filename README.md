# 2022-VR-dynamic-GrIS

This repository contains the analyzing and plotting scripts and the resulting plots for paper Yin et al. (2025) "Improved Understanding of Multicentury Greenland Ice Sheet Response to Strong Warming in the Coupled CESM2-CISM2 With Regional Grid Refinement" published on *Journal of Advances in Modeling Earth Systems* [https://doi.org/10.1029/2024MS004310](https://doi.org/10.1029/2024MS004310)


## Contents

| Directory | Description |
|------------|------------|
| Figure 1 | CESM2 variable-resolution Arctic grid and topography |
| Figure 2 | Evolution of climate forcing, temperature, mass balance, and surface energy balance |
| Figure 3 | Simulated Greenland Ice Sheet albedo, surface mass balance, thickness, and velocity changes |
| Figure 4 | Greenland Blocking Index evolution |
| Figure 5 | Atmospheric circulation changes: 500 hPa geopotential height |
| Figure 6 | Lower-tropospheric and near-surface temperature differences |
| Figure 7 | Ocean circulation, freshwater flux, and sea ice evolution |
| Figure 8 | Greenland Ice Sheet mass balance, volume loss, and sea-level contribution |
| Figure 9 | Spatial differences in precipitation, refreezing, melt, and ice thickness |
| Figure 10 | Cloud liquid water and surface radiative flux differences |
| Figure 11 | Melt energy and surface energy balance component differences |
| Figure 12 | Evolution of surface energy balance component differences |
| Figure 13 | Greenland Ice Sheet melt–albedo feedback differences |
| Figure 14 | Surface albedo evolution and temperature relationships |
| Figure 15 | Area–elevation distributions and ice sheet–climate model elevation consistency |
| Figure 16 | Equilibrium line altitude and ablation area evolution |
| Supplementary | Scripts used to generate supplementary figures and analyses |


## Data

The analyses use output from coupled CESM2-CISM2 simulations.

The model simulations include:

- Standard 1° CESM2 configuration
- Variable-resolution CESM2 configuration with ~0.25° resolution over the Arctic

Simulation output is stored on NCAR HPC systems and is not included in this repository because of file size limitations.

Users interested in the raw model output should contact the corresponding author.

Preprocessed data used by the analyzing and plotting scripts are stored in an open repository Zenodo (Herrington & Yin, [2024](https://zenodo.org/records/15049546)).


## Notes

- Raw model output is not distributed through this repository.
- Some scripts contain local file paths that must be modified before execution.
- HPC-specific preprocessing scripts are not included.


## Contact

Ziqi Yin

Department of Atmospheric and Oceanic Sciences

University of Colorado Boulder

Email: ziqi.yin@colorado.edu
