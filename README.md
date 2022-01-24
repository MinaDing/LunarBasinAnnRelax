# LunarBasinAnnRelax
This repository includes our simulation results for the post-impact viscoelastic relaxation of crustal annulus for lunar impact basins using Abaqus, especially for reproducing Figs. 4 & 5 in our submitted paper. 
- Folders Fig4(a-d) are simulation results of four test cases. In each folder, Txx_Start.rpt and Txx_End.rpt list the coordinates of crustal nodes in the beginning (after gravitational collapse) and at the end of a Abaqus run, respectively. HeatFlux.rpt is the reference heat flux with time (Fig. 4e), AnnulusTemp.rpt provides the avarage temperation of the crustal annulus (in our Fig. 4f), and AnnulusVerDisp.rpt provides the mean depth of the annulus materials (Fig. 4g). A matlab code PlotResult.m is provided to plot these results. 
- Excel file Fig5_ModelSensitivity.xlsx provides all the data points (test model results) necessary to reproduce Fig. 5. 
