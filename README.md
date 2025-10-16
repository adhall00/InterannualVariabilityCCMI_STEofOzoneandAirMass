
### Purpose of this Repo
This repository will show you how to perform a multiple linear regression (MLR) with the Brewer Dobson Circulation, Quasi-Bienniel Oscillation, and the El Nino Southern Oscillation as predictors for the Stratosphere-Troposphere Exchange of Ozone and Air mass from 1980 to 2020. 

### The Steps Before the MLR
#### 1. Constructing the ENSO index...
To create the ENSO index we will use the nino3.4 index "rules" 

a. we choose the nino3.4 region (120-170W and -5S-5N), this is off the west coast of Peru/Ecuador into the Pacific Ocean.

b. find sst anomalies derived as deviations from the 1980 to 2020 (41 year average) sst climatology

c. weight the anomalies by cosine(latitude) for the area weighting

d. normalize the sst anomaly time series by the standard deviation

e. apply a five month running mean to the time series. We would use a three month running mean for the ONI


[NOAA guidelines for constructing the Nino3.4 Index](https://www.ncei.noaa.gov/access/monitoring/enso/sst)

[Climate Data Guide](https://climatedataguide.ucar.edu/climate-data/nino-sst-indices-nino-12-3-34-4-oni-and-tni)

#### 2. Constructing the QBO index...

#### 3. Constructing the BDC index...
