# GC_Larval_SMB

These files are intended for use in modeling growth in fish from seining data for larval and small bodied fish in the western Grand Canyon (mile 88-279) from 2014-2021. 

Files included in this reposity are:

A. Two files of R code in which I have 
  1. re-formatted and organized environemnetal/habitat data from USGS stream gages on the Colorado River. Data at Pearce Ferry were extrapolated from gage data available at Bright Angel, National, and Diamond Confluences using lm(), then data for river miles in between these gages was interpolated using approx() in R  (Organize_Enviro_Data), and
  2. re-formatted and organized data from seine hauls. These data are split into two categories, reflecting general age class of fish (larval vs. small bodied) and types of length data collected (standard length vs. total length). (Organize_LarvalSMD_Data)
  
B. Original data files that include the raw larval and small bodied fish data, as well as the data from the USGS Stream Gages

C. The formatted files for BHS, SPD, FHM, FMS, HBC and RBS, in excel format, that are ready to be used in growth models.
