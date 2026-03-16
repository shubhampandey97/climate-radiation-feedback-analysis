# Climate Radiation Feedback Analysis

This project analyzes Earth's radiation budget using CMIP6 climate model simulations and CERES satellite observations.

## Objective
Estimate the climate feedback parameter (λ) using Net Top of Atmosphere radiation and surface temperature.

## Dataset
- CMIP6 Models
  - CESM2
  - IPSL-CM6A-LR
  - MPI-ESM1-2-LR
- CERES Satellite Observations

## Data

Due to large file sizes, datasets are not included in this repository.

Download the datasets from:

CMIP6:
https://esgf-node.llnl.gov/projects/cmip6/

CERES:
https://ceres.larc.nasa.gov/data/

Place the downloaded files in:

data/

## Tools Used
- Python
- Xarray
- NetCDF
- Matplotlib
- Climate Data Analysis

## Workflow
1. Load NetCDF climate datasets
2. Compute global mean radiation
3. Calculate temperature anomalies
4. Estimate climate feedback parameter (λ)
5. Compare models with observations

## Results
Estimated feedback parameters:

| Dataset | λ (W m⁻² K⁻¹) |
|-------|-------|
| IPSL |  -0.5135236877118935 |
| CESM2 | -0.9377436794459524 |
| MPI-ESM | -1.151372775094319 |
| CERES | -1.0477615014825876 |

## Visualization

Radiation imbalance comparison between CMIP6 models and CERES observations.