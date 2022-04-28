# ede_mnu

## Description
The corresponding plotting code and chains for a project where an EDE model is explored in the context of a free neutrino mass. Arxiv link: 

Notebooks are as follows: 

* BAO_positions: reproduce figure 3 from the paper i.e. the BAO position as a function of redshift for different best-fit neutrino mass models 
* corner_plot: import chains and plot the contours for the MCMC analysis
* compare_multipoles: compare the redshift-sapce multipoles with the data for each of the best-fit cosmologies. The main take-away is that clustering amplitude can mostly be re-absorbed by varying the nuisance parameters and the main constraint comes from shape information
* param_shifts: show how the position of $\theta_{BAO}$ varies when parameters in the EDE+$M_\nu$ model are varied
* vary_mnu_exploration: show how the predicted non-linear matter power spectrum and CMB TT spectrum vary as the value of $M_\nu$ is varied whilst keeping other parameters fixed


### Set-up to run code 
git clone https://github.com/Michalychforever/EDE_class_pt.git 
follow instructions to make CLASS_PT from https://github.com/Michalychforever/CLASS-PT 

### Install requirements
python -m pip install -r requirements.txt
