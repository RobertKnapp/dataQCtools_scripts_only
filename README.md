# dataQCtools_scripts_only
Working Repo for enhancement of dataQCtools for use by JST and others

Copied folder structure (dataQCtools_scripts_only/extdat/data/2022_summer/1_raw_csv) from dataQCtools package repo. created scripts by copying code from https://tribalxg.github.io/dataQCtools/ website. Three scripts placed in extdata directory (crop_raw_data.R, make_qc_plots.R, and compuing_7DADM_indentifying_site_impairments.R). 

As of 2025-08-04, this script is custom designed to work with Onset/LI-COR HOBO  Water Temper Pro v2 data loggers. Logger data must be extracted from each sensor/logger using the HOBOware Pro sofware package using either the Optic USB Base Station or the HOBO waterproof Shuttle (U-DTW-1). All raw datasets must be saved to the 1_raw_csv directory. In addition to the raw data files, the code will be expecting an MS Excel document m labeled "LDRTimes.xlsx" The LDRTimes file site, media, deploy_time, retrival_time, deploy_season, deploy_year attributes must be filled in for the code to perform correctly. 

<img width="1192" height="119" alt="image" src="https://github.com/user-attachments/assets/697beb08-b27e-46d4-86fd-05f069604715" />

