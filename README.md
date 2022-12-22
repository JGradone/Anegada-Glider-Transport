# Anegada-Glider-Transport

This repository contains the code used in the analysis performed in Gradone et al. (2023): Upper Ocean Transport in the Anegada Passage from Multi-Year Glider Surveys

The dataset used in this analysis can be found here: https://doi.org/10.5281/zenodo.7468695. This dataset contains glider-acoustic doppler profiler observations from four glider deployments in the Anegada Passage region from 2020-2022. The 2020-2021 data are from a Nortek AD2CP and the 2022 data are from a Teledyne RDI Pathfinder. The RDI Pathfinder .PD0 files can be read directly in this code.  The Nortek AD2CP .ad2cp files are processed using Nortek's MIDAS software to generate NetCDFs.


Work-Flow
----------------------
These notebooks are labeled with the prefix 01_, 02_, 03_, etc. to show the order of operations.

01_ notebooks
----------------------
This notebook was used to become familiar with the data and some of the processing steps through a quick data exploration.

02_ notebooks
----------------------
This notebook was used to pre-process the AD2CP data. Additional information is included in the notebook.

03_ notebooks
----------------------
This notebook was used to take the data processed in the 02_ notebook, read in glider data using ERDDAP, perform a least squares linear inversion to extract horizontal velocity profiles, and save the output.

04_ notebooks
----------------------
This step is the analysis!


Acknowledgments
----------------------
Citations for the methods used in this package are included in the code where relevant. This repository was designed using Cookiecutter Data Science: https://drivendata.github.io/cookiecutter-data-science/

