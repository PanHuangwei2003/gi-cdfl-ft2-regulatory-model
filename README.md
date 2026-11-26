## Repository structure

- **data/**: Experimental data and model input data.
- **figures/**: Figures generated from computational analyses.
- **parameters/**: Fitted parameters used in model simulations.
  - **gaussian_input_parameters/**: Fitted parameters of Gaussian input functions.
  - **model_parameters/**: Fitted parameters of the dynamical models.
- **src/**: Source code for model construction, parameter estimation, and simulation.
  - **gaussian_fitting/**: Code for fitting Gaussian functions to experimental profiles.
  - **pttft2_model/**: Implementation of the PttFT2 regulatory model.
  - **scripts/**: Scripts for model fitting, simulation, evaluation, and figure generation.

## Environment setup

The computational environment was managed using Conda. The required dependencies and package versions are specified in `environment.yml`.

To create and activate the environment, run:

```bash
conda env create -f environment.yml
conda activate pttft2_env
```
