# 2022-VR-dynamic-GrIS

This repository contains the analyzing and plotting scripts and the resulting plots for paper Yin et al. (2025) "Improved Understanding of Multicentury Greenland Ice Sheet Response to Strong Warming in the Coupled CESM2-CISM2 With Regional Grid Refinement" published on *Journal of Advances in Modeling Earth Systems* [https://doi.org/10.1029/2024MS004310](https://doi.org/10.1029/2024MS004310)


## Contents

| Figure | Description |
|------------|------------|
| [Figure 1](script/compare_topography.ipynb) | CESM2 variable-resolution Arctic grid and topography |
| [Figure 2](script/tseries_CO2_T2m_GrISarea_MB_SMB_SEB.ipynb) | Evolution of climate forcing, temperature, mass balance, surface mass balance, and surface energy balance |
| [Figure 3](script/map_albedo_SMB_thk_vel.ipynb) | Simulated Greenland Ice Sheet albedo, surface mass balance, thickness, and velocity changes |
| [Figure 4](script/compare_GBI.ipynb) | Greenland Blocking Index evolution |
| [Figure 5](script/compare_Z500.ipynb) | Atmospheric circulation changes: 500 hPa geopotential height |
| [Figure 6](script/compare_temp_JJA_troposphere_surface.ipynb) | Lower-tropospheric and near-surface temperature differences |
| [Figure 7](script/compare_NAMOC_ff_sea_ice_extent_thickness.ipynb) | Ocean circulation, freshwater flux, and sea ice evolution |
| [Figure 8](script/tseries_precip_melt_refrz_SMB_MB_ivol_slr.ipynb) | Greenland Ice Sheet mass balance, volume loss, and sea-level contribution |
| [Figure 9](script/compare_precip_refrz_melt_dthk.ipynb) | Spatial differences in precipitation, refreezing, melt, and ice thickness |
| [Figure 10](script/compare_cloud.ipynb) | Cloud liquid water and surface radiative flux differences |
| [Figure 11](script/compare_ME_SEB.ipynb) | Melt energy and surface energy balance component differences |
| [Figure 12](script/tseries_SEB.ipynb) | Evolution of surface energy balance component differences |
| [Figure 13](script/compare_albedo_feedback.ipynb) | Greenland Ice Sheet melt–albedo feedback differences |
| [Figure 14](script/compare_albedo.ipynb) | Surface albedo evolution and temperature relationships |
| [Figure 15](script/compare_topography.ipynb) | Area–elevation distributions and ice sheet–climate model elevation consistency |
| [Figure 16](script/compare_ablation.ipynb) | Equilibrium line altitude and ablation area evolution |
| [Figure S1](script/compare_albedo_feedback.ipynb) | Examples of albedo feedback calculation |
| [Figure S2](script/compare_cloud.ipynb) | Additional cloud and radiation variable differences |
| [Figure S3](script/compare_humidity_sea_ice_impact.ipynb) | Evolution of Greenland Ice Sheet-averaged temperature and humidity |
| [Figure S4](script/compare_humidity_sea_ice_impact.ipynb) | Sea ice concentration and evaporation differences |
| [Figure S5](script/compare_ME_SEB.ipynb) | Surface energy balance differences during the pre-industrial period |
| [Figure S6](script/compare_ME_SEB.ipynb) | Surface energy balance differences with initial differences removed |
| [Figure S7](script/compare_albedo_feedback.ipynb) | Greenland Ice Sheet albedo feedback maps |
| [Figure S8](script/compare_topography_cross_components.ipynb) | Surface elevation differences |
| [Figure S9](script/compare_transect.ipynb) | Atmosphere model surface elevation along transects |
| [Figure S10](script/compare_topography.ipynb) | Hypsometric cumulative area–surface elevation relationships for different basins |


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
