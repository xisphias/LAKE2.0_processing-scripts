Atgasuk Lake pre/post-processing workflow: 

1. open USGS_SM_Atgasuk_data_preprocess-v0.ipynb and run preprocess_Atgasuk function. It will produce the data/Atgasuk.dat.  
to run pre-processing script successfully make sure Atgasuk_lake_NS/South Meade.txt and Atgasuk_lake_NS/atqasuk-atq-2014-2015-meteorology-timeseries-calon.csv are in right folders (see preproccess_Atgasuk_met_data.py) 
2. run the model
3. use post-proces_Atgasuk_LAKE_results_v0 to plot the results
4. go back to step, change the wprecip: and p_reduce, do steps 1-3. in step 3 check difference between previous and current results.