# Main working directory for SpE project notebooks 
## /localhome/sestay/jupyter_new  mynewenv & mynewkernel

## Contents : Notebooks:
    
- **COSMIC_Daviddata_data_processing.ipynb**
  - Processing (and plotting) COSMIC dataset sent from David Themens - to put into desired bins and calculate occurence freq
- **COSMIC_Daviddata_Mag_Lats_Interp.ipynb**
  - Interpolating David's (processed) COSMIC data onto magnetic latitude, and plotting lat-line plot with equivalent WACCM data
- **COSMIC_WACCM_Plotting-Daviddata-FINAL_CRITERIA_0.25sigma_2xMpza_1peak.ipynb**
  - Figure plotting COSMIC & WACCM occurence frequency comparison plots for paper
- **Other COSMIC_WACCM_Plotting-Daviddata... notebooks**
  - Plotting figures from sensitivity studies - each criteria set individually
- **Criteria_Sensitivity_Plots.ipynb**
  - Plotting figures comparing sensitivity studies for the Supplementary Info - Combined figs for multiple criteria sets
- **E_layer_densities_and_Crit_freqs.ipynb**
  - Interrogating the M+ densities and critical frequencies where Es layers are identified by the algorithm, and plotting histograms
- **Es_ID_Combine_Imgs.ipynb**
  - Combining images for different criteria sets from Figures/Wuhu_IonTr_run/Es_ID (Individual_Es_Plot.ipynb) - Plots of individual Es events for criteria A, H, I and M
- **Individual_Es_Plot.ipynb**
  - Plotting individual Es layer occurence events (alt vs local time) in June and Dec
- **Mag_Lats_Contour_Lines.ipynb**
  - Loading/plotting magnetic contour line data from Wuhyu's 3 metal run, to use in plots of WACCM vs COSMIC occ freqs
- **Solar Irradiance.ipynb**
  - Creating WACCM input files for solar min/max model runs (ssi, tsi, f107, kp, ap etc)
- **SpE_Id_Algorithm_2023-12-07-NEW.ipynb**
  - Main SpE identification algorithm 
- **WACCM_Mag_Lats_Interp.ipynb**
  - Interpolating WACCM Es occurrence freq data onto magnetic latitude
- **WACCM_Winds.ipynb**
  - Plotting U and wind shears from WACCM-X overlayed with SpE/M+
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
    
