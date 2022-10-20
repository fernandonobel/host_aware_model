# Host-aware model

## Files and folder structure

- `./build` 

  The folder where OneModel stores the auto-generated Matlab implementations of
  the host-aware model. Do not make changes to the files inside this folder, as
  they will be overwritten if we use OneModel to generate new implementations
  of the host-aware model.

- `./matlab`

  Matlab code for running the model.

- `./matlab/data`
 
  Here I save scripts with the data for performing simulations.

- `./matlab/figs`
 
  I use this folder to store the simulations figures.

- `./matlab/utils`
  
  This folder stores auxiliary scripts and functions.

- `./matlab/initialize.m`
  
  You need to call this script at the beginnign to setup thepath in Matlab.

- `./matlab/simulateMassDistribution.m`
 
  A test simulation for validating that the host-aware model is okey.

- `./matlab/example_oneprotein.m`
  
  An example script of simulating the host-aware model with the expression of
  one exogenous protein.

- `./src`

  This folder stores the OneModel models that we use to generate the Matlab
  code.



