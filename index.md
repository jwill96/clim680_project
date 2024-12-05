# Comparing Sea Surface Temperature Anomalies from JAMSTEC ARGO Float Data to NOAA ERSST V5 SST anomalies for Nino 3.4. 

## by: Jaedyn Williams

## Introduction:
The first set of data is analyzed Argo data from JAMSTEC (Japan Agency for Marine-Earth Science and Technology). The temperature and salinity profiles are obtained from Argo floats. The Argo floats drift with the ocean currents. The floats descend to 2,000 meters every 10 days and collect a vertical profile of temperature and salinity. The index that was used to compare with the JAMSTEC data was the NOAA ERSST V5 SST anomaly for Nino 3.4. Nino 3.4 is the SST for the East Central Tropical Pacific. 

## Data:
JAMSTEC Argo Float Data: 
- 1 x 1 degrees horizontal resolution
- standard pressure levels from 10 to 20000 dbars
- I worked with the TOI (temperature) and SOI (salinity) variables
- data range: 2021-2024

El nino 3.4 Data: East Central Tropical Pacific SST Mean Values (5N-5S)(170-120W) from CPC
https://psl.noaa.gov/data/correlation/nina34.data

## Code Description:
The following link goes to the ipynb code in github. https://github.com/jwill96/clim680_project/blob/main/CLIM%20680_project.ipynb

![image](https://github.com/user-attachments/assets/59d75dcc-29fd-4ff6-83d9-b29f3429193c)

Figure 1. Shows the SST anomalies for Nino 3.4. 

![image](https://github.com/user-attachments/assets/cb2eaed9-2244-4104-ad1b-0b5f9c1d411b)

Figure X. Sea Surface Temperature Anomalies for 2024 compared to Climatology 2001-2022 JAMSTEC data

![image](https://github.com/user-attachments/assets/d942db38-d800-4d73-b36c-d091423f5ba7)

Figure X. Sea Surface Salinity Anomalies for 2024 compared to Climatology 2001-2022 JAMSTEC data

![image](https://github.com/user-attachments/assets/07db89c5-20fb-4efd-8eb7-3a626d7f1442)


Figure X. Sea Surface Temperature Anomalies for 2024 compared to Climatology 2001-2023 JAMSTEC data
The SST anomalies for January, February, and March show positive anomalies in the Pacific Ocean moving toward the Gulf. The data also shows that there are positive anomalies in the Atlantic as well as the Indian Ocean. 

![image](https://github.com/user-attachments/assets/ba10cabb-b9eb-4465-90dc-131a23cf4c13)


Figure X. Sea Surface Salinity Anomalies for 2024 compared to 2001-2023 JAMSTEC data
The SSS anomalies from January to May for 2024 show that there are negative SSS anomalies primarily in the Indian Ocean.




## Results:
The results show that the SST and SSS anomalies for 2024 compared to the 2001-2023 climatology data have a negative correlation. When there are positive SST anomalies in certain regions, there are negative SSS anomalies present. The negative SSS anomalies are the largest in the Indian Ocean even though the largest positive SST anomalies are seen in the Pacific and Atlantic Oceans. 

## Summary:
One of the greatest challenges for working with the data that I selected was being able to work with a large set of data. The data from JAMSTEC was separated by year and month so there were over 276 files of data that I was working with.

## References: 
https://www.jamstec.go.jp/argo_research/dataset/moaagpv/moaa_en.html

https://www.cpc.ncep.noaa.gov/data/indices/ersst5.nino.mth.91-20.ascii

https://climatedataguide.ucar.edu/climate-data/nino-sst-indices-nino-12-3-34-4-oni-and-tni

https://psl.noaa.gov/data/correlation/nina34.data
