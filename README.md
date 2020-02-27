# climate-learning

This is a place to develop ideas, designs and machine learning models to study climate change. 

# reference information
The project utilizes the landscape dynamics resources from the National Park Service (NRSS I&M Division). Further information about the landscape dynamics program and monitoring environmental setting for National Park Service units can be found here:

https://irma.nps.gov/DataStore/Reference/Profile/2258457

https://www.nps.gov/im/landscape-dynamics.htm

The main dataset of interest is PRISM 800m gridded climate data. Source information for PRISM data can be found here:

http://www.prism.oregonstate.edu/


# preliminary dataset and analysis

The first dataset consisted of 800m gridded Prism data for climate metrics taken from an Area of Analysis (AOA) delineated by the boundary of Tallgrass Prairie National Preserve (NPS TAPR) plus a 30 km buffer area. Metrics included mean monthly values for mintemp, maxtemp and precip. Temp values were deviations from 30 yr normals while precip values were monthly averages for 30 yrs (1987 to 2016).

Preliminary analysis consisted of timeseries plots for mean monthly mintemp, maxtemp and precip. Timeseries of deltas (change from month t to month t + 12 months) were also plotted. Simple histograms were developed for dates associated with: the hottest upper quartile of months (mean monthly maxtemp), coldest quartile (mean monthly mintemp) and driest and wettest quartiles (mean monthly precip).


# plans

Determine some methods to calculate and display ARIMA model parameters for each grid cell. Learn more about timeseries statistics and timeseries package in R.




