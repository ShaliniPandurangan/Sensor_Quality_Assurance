# Sensor Quality Assurance
This repository contains the code that has been used to assure the quality of the new IMU sensors from Oureka. The data from the Shimmer sensor has been used as a benchmark. 

## Contents
### Helper functions

1. Function norm(): A function that calculates the takes a dataframe and calculates the norm of all the columns in the dataframe. 

2. Function denoise(): A 1D guassian filter to remove the noise based on the standard deviations 

3. Function Average(): A function that takes a list as input calculates the average. 

4. Function auc(): A function that uses numpy to calculate the area under the curve for the absolute values of the dataframe.


## Static data analysis 

This section analyses the data sampled when the sensor is places static without movements. 

Experiment settings parameters include:

IMU sampling rate