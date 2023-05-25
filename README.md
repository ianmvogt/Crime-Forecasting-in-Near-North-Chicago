# Crime-Forecasting-in-Near-North-Chicago
Time series analysis and forecasting of hourly crime in Chicago's Near North neighborhood. This area includes the location of the University of Chicago M.S. in Applied Data Science program, Booth School, and residential location for many students. Chicago has a negative reputation regarding crime, but is this justified? We can gain insights into Chciago crime activity through the Crimes 2001 - Present data extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system.

Data Source: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present-Dashboard/5cd6-ry5g

The dataset contains non-uniform timestamped log of crime activity throughout all of Chicago. Analysis can be performed on a neighborhood level using the 'Community Area' variable (Near North neighborhood = Community Area 8). This leads to the problem statement: When do members of University of Chicago Booth and M.S. in Applied Data Science programs need to be most vigilant regarding local crime?

I perform daily and hourly aggregation of crime activity tagged in Community Area 8 to convert the data to a uniform time-series. I utilize the daily data for EDA but forecast on the hourly level and compare the performance of ARIMA, Seasonal ARIMA, and Prophet Models.
