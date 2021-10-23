[![DOI](https://zenodo.org/badge/420248298.svg)](https://zenodo.org/badge/latestdoi/420248298)

# LAKE2.0_processing scripts
 Processing scripts for LAKE2.0 model input and output

Pre-processing
	Toolik
		formatToolikhrly_final.R
			Used to format toolik met data for model
		formatToolikLakeInterpolate_final.R
			Used to combine measured lake temp data and interpolate to regular 1m grid
		ToolikDischarge_final.R
			Used to process raw discharge measurements to inflow and outflow files for model
	FoxDen
		formatFoxDenDay_final.R
			Used to format foxden met data for model
	Atqasuk
		none
	All
		standardizeLakeTempData.R
			Used to standardize measured lake water temperature data for use with post processing scripts.

Post-processing
	All
		plotLaketemp_Final.R
			Plot LAKE model temp data compared to obs data and met data. Figs 1-4 in paper. 
		plotLakeTempScenariosCM_final.R
			Calculate errors for scenarios, Combine errors for color matrix plot. Fig 5
		plotLakeTempScenariosCM_season_final.R	
			Calculate errors for scenarios with seasons, Combine errors for seasonal barplot. Fig 6		

