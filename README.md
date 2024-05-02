# Main working directory for SpE project notebooks 
## /localhome/sestay/jupyter_new  mynewenv & mynewkernel

## Contents : Notebooks:
    
- **COSMIC_Daviddata_data_processing.ipynb**
  - Processing (and plotting) COSMIC dataset sent from David Themens - to put into desired bins and calculate occurence freq
- **COSMIC_Daviddata_Mag_Lats_Interp.ipynb**
  - Interpolating David's (processed) COSMIC data onto magnetic latitude, and plotting lat-line plot with equivalent WACCM data
- **COSMIC_WACCM_Plotting-Daviddata.ipynb**
  - Figure plotting COSMIC & WACCM occurence frequency comparison plots for paper
- **E_layer_densities_and_Crit_freqs.ipynb**
  - Interrogating the M+ densities and critical frequencies where Es layers are identified by the algorithm, and plotting histograms
- **Individual_Es_Plot.ipynb**
  - Plotting individual Es layer occurence events (alt vs local time) in June and Dec
- **Mag_Lats_Contour_Lines.ipynb**
  - Loading/plotting magnetic contour line data from Wuhyu's 3 metal run, to use in plots of WACCM vs COSMIC occ freqs
- **Solar Irradiance.ipynb**
  - Creating WACCM input files for solar min/max model runs (ssi, tsi, f107, kp, ap etc)
- **SpE_Id_Algorithm_2023-12-07.ipynb**
  - Main SpE identification algorithm 
- **WACCM_Mag_Lats_Interp.ipynb**
  - Interpolating WACCM Es occurrence freq data onto magnetic latitude
- **Working_directory.ipynb**
  - Change current working directory for python notebooks (this got out of sync once which caused an issue)
    
## Contents : Folders:

- **'Nc_files' folder**
  - All input files are pulled from here (all folders within here are symbolic links from other places to prevent repo from getting too large)
- **'Figures' folder**
  - All output figures are saved in here
- **'Old_Notebooks' folder**
  - Contains various old/unused notebooks e.g. from before I was using version control/old methods/whatever
- **'Wuhu_WACCMXrun_notransport' folder**
  - Contains plotting for an equivalent model run with no metal ion transport added, for comparison purposes. The contents haven't been checked/edited in a long time...
    
