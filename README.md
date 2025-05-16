# hei-sporo-code

This repository is the overview repository for an upcomming publication on Plasmodium sporozoite movement.
It contains some code for STED analysis, and has two main related repositories:
github.com/LeonLettermann/hei-sporo-code-tracking   ---> Contains code for image analysis, tracking & traction force analysis
github.com/LeonLettermann/hei-sporo-code-simulation ---> Contains code for simulation of sporozoite gliding motility
Data files to test the code provided here can be found in the data repository https://doi.org/10.11588/DATA/4YBYXE .

This repository contains
|____environment.yml        --->  Conda environment for this and the linked repositories.
|                               !! JAX version might need to be adapted depending on your system !!
|____STED                   ---> Folder containing example script for STED analysis
| |____AnalyzeSTED.ipynb    ---> Containin angular profile generation and microtubule position inference
