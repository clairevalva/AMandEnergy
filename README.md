# AMandEnergy
Repo for data analysis of annular modes (BAM and SAM) and connection to the energy cycle — particularly would like to see if there is any changes in the 40 years of ERA5 data. Uses ERA5 and UCAR JupyterHub for computing, a project for OP's atmospheric dynamics class in CAOS/Courant.  

I make reference to Thompson and Woodworth 2014 often (https://doi.org/10.1175/JAS-D-13-0185.1).

files:
- `processing.ipynb`: in which I process monthly ERA5 data into zonal mean and eddy components. Also compute terms like total heat flux and eddy kinetic energy for later use.
- `regression_analysis.ipynb`: where I compute BAM/SAM indices from the monthly data and use regression analysis to related these indices with variable variables related to energy transport etc. This ends up not being consistent with the Thompson and Woodworth 2014 paper.
- `daily_exploration.ipynb`: where I attempt to compute BAM/SAM indices from daily data and want to compare the behavior of the indices (such as power spectra) over the 40 years of data. (In progress.) 
