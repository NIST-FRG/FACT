# FACT 
**F**lammability data **A**utomated **C**alibration **T**ools

*A suite of tools and data in support of predictive fire modeling.*

The tools within FACT can rapidly determine material parameter inputs needed for making robust and accurate computational predictions of fire growth for a broad range of materials. Such predictions can support the development of reduced flammability materials and a safer built environment. 
These tools are developed as part of the NIST [Material Flammabiilty Characterization Project](https://www.nist.gov/programs-projects/material-flammability-characterization). 
Related [FACT publications and overview presentations](https://www.nist.gov/programs-projects/automated-tools-material-property-calibration) are available online.

Note that FACT is still in development. Currently, tools exist for 
1. Extracting pyrolysis kinetic parameters from thermogravimetric analysis (TGA) data, 
2. Extracting heats of combustion from microcombustion calorimetry (MCC) data,
3. Extracting specific heat capacities and heats of pyrolysis from differential scanning calorimetry (DSC) data, and
4. Extracting conductivities from Gasification data.

A minimum working example (MWE) of experimental data for testing FACT is found in the "Experiment" folder. Scripts for fitting this data are contained in the "Scripts" folder. After a fit has been performed, CSV files and plots of the model predicted data are written to the "Fits" folder. Additionally, the calibrated model parameters are written to a JSON file under "Materials/properties".

This work is being done in conjunction with the development of an experimental database in support of the International Association of Fire Safety Science (IAFSS) [Measurement and Computation of Fire Phenomena (MaCFP) working group](https://github.com/MaCFP/matl-db).
