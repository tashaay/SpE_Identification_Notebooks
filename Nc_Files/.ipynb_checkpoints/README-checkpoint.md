- All folders within here are symbolic links from other places. 
- This is to prevent the repo from getting to large to sync, which can cause issues, even if it's then rectified/files are removed


**ACP_CESM213_FX2000_f19_f19_mg16_Na_Fe_Mg_iontransport**
- Symbolic link, points to -> /usr/not-backed-up/earfw/ACP_CESM213_FX2000_f19_f19_mg16_Na_Fe_Mg_iontransport/
- Wuhu's 3 metal run WACCM output

**CESM213_FX2000_f19_f19_mg16_Na_Fe_Mg_Si_Ca_K_iontransport**
- Symbolic link, points to -> /usr/not-backed-up/earfw/CESM213_FX2000_f19_f19_mg16_Na_Fe_Mg_Si_Ca_K_iontransport/
- Wuhu's 6 metal run WACCM output
 
**e_histogram** 
- Symbolic link, points to -> /usr/not-backed-up/sestay/e_histogram
- Output from *'E_layer_densities_and_Crit_freqs.ipynb'* notebook

**Jianfei_WACCMX_files**
- Symbolic link, points to -> /usr/not-backed-up/sestay/Jianfei_WACCMX_files/
- Jianfei's model run WACCM output, equivalent to Wuhu's 3 metal run

**s4max**
- Symbolic link, points to -> /usr/not-backed-up/sestay/s4max
- **Output** from **COSMIC data processing** notebooks:
    - ***'Daviddata'*** folder contains all relevant files
        - Individual Readmes in each folder
    - **All other files/folders** are **OLD OUTPUT** from previous data processing attempts
        - </u>**IGNORE ALL THESE FILES/FOLDERS**</u>

**s4max_files**
- Symbolic link, points to > /localhome/sestay/s4max_files/
- **Input** to **COSMIC data processing** notebooks:
    
    **Used for paper**
    - **COSMIC1_for_Leeds.h5**
        - Dataset from David Themens <d.r.themens@bham.ac.uk> More info on dataest in *'COSMIC_Daviddata_data_processing.ipynb'* notebook
        
    **Historic Data, now unused, from old COSMIC data processing**
    - 1_s4max.nc
        - COSMIC s4max dataset, variables: Ut_time, altitude, DOY, lat, LT (local time), lon, mlat (magnetic lat), mlon (magnetic lon), mlt (magnetic LT), s4max, year. Dimensions for all: nfile(9266536). Sent from chinese group to Wuhu. Data is also downloadable from COSMIC-1 website.    
    - mod_s4max.nc 
        - Same as '1_s4max.nc' but added coordinates for altitude, lat, lon, time, season, month. Data processed in *'Old_Notebooks/COSMIC_23-09_s4_data_transformation step 1.ipynb'* notebook.
    - mod_s4max_80-130km.nc
        - Same as 'mod_s4max.nc' but sliced between 80 and 130 km. Dimensions for all variables: nfile(6449380). Data processed in *'Old_Notebooks/COSMIC_23-09_s4_data_transformation step 1.ipynb'* notebook.
    - s4max_raw_2007_2018.h5 
        - Downloaded from COSMIC-1 website https://cdaac-www.cosmic.ucar.edu/cdaac/cgi_bin/fileFormats.cgi?type=scnLv1

**SpE_Output**
- Symbolic link, points to -> /usr/not-backed-up/sestay/SpE_Output
- Output from *'SpE_Id_Algorithm_2023-12-07.ipynb'* notebook: WACCM data (Wuhu's 3 metal run), processed season by season, calculating occurence freq etc
- 'Mag_Coords' folder:
    - 'Occ_Fr_maglat_lon.nc' is output from *'WACCM_Mag_Lats_Interp.ipynb'* notebook: WACCM occurrence frequency interpolated onto magnetic latitude
    - 'Mag_lat_contours.nc' is output from *'Mag_Lats_Contour_Lines.ipynb'* notebook: ALATM (Magnetic latitude at each geographic coordinate) variable

**spectral_files**
- Symbolic link, points to -> /localhome/sestay/spectral_files
- Output from *'Solar Irradiance.ipynb'* notebook : generating NC files for new SpE SMin and SMax runs
- Also contains solar files that were used in Wuhu's WACCM run used to produce the above