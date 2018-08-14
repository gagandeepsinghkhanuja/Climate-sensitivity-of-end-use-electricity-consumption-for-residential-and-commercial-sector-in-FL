# Climate-sensitivity-of-end-use-electricity-consumption-for-residential-and-commercial-sector-in-Florida-United-States
My analyses was implemented for the state of Florida, one of the most energy intensive states with geographic and demographic vulnerability to climatic change. I leveraged various linear and  non-linear statistical learning methods to develop predictive models for residential and commercial electricity usage to understand the relationship between weather, climate and electric power consumption.I have assessed the models performance on the basis of goodness of fit and predictive accuracy to select the best model based on both generalizabilty and the ability to capture structure of data. The selected models were then used to understand the climate sensitivity of load in both residential and commercial sectors. 


# Data Source
The data on end use electricity consumption, climate and weather, and socio-economic information was obtained from various publicly available data sources such as U.S. Energy Information Administration (EIA), National Oceanic and Atmospheric Administration (NOAA), National Climatic Data Center (NCDC) and U.S Department of Labor, Bureau of Labor Statistics. 

Input Data Preparation
The four categories of input variables, namely electricity data, climate data, weather data and socio-economic data. They are :

1. Electricity data
Electricity consumption data was obtained from the U.S. Energy Information Administration (EIA).The monthly electricity sales data of the residential and commercial sectors during the period of 1990-2015 was extracted from the database for the state of Florida.

2. Climate data
Monthly climate data was requested from National Oceanic and Atmospheric Administration (NOAA), starting from 01-Jan1989 to 01-Jan-2016. The data was collected from 18 stations spread throughout Florida, mostly located in the top large or medium-sized cities of the state. The climate data contains three different data types: degree-days (derived variables), temperature (tenth of Celsius), precipitation (tenth of mm precision).

3. Weather data
Weather data ranging from 01-Jan-1990 to 31-Dec-2015 was requested from National Climatic Data Center (NCDC). The weather data was collected on a daily basis and it is recorded at multiple weather stations located across the state of Florida. The various weather variables include: mean wind speed, maximum wind speed, visibility,4 maximum wind gust,5 mean dew point temperature (MDPT), daily air temperature, and maximum daily temperature. 

4. Economic data
The economic data was obtained from the U.S. Department of Labor, Bureau of Labor Statistics. The dataset includes variables
such as employment, unemployment, unemployment rate, gross state product (GSP), per capita income of the population and labor force.



# References

[1] EIAForm826(CurrentFormEIA861M)DetailedData,2016:Salesandrevenue(Aggregated:1990-current) ohttps://www.
eia.gov/electricity/data/eia861m/4.

[2] USDL.BureauofLaborStatistics:DataTools.UnitedStatesDepLabor,2016. 〈http://www.bls.gov/data/〉.

[3] D.J.Sailor,J.R.Muñoz,SensitivityofelectricityandnaturalgasconsumptiontoclimateintheU.S.A.—Methodology and
results foreightstates,Energy22(1997)987–998. http://dx.doi.org/10.1016/S0360-5442(97)00034-0.
