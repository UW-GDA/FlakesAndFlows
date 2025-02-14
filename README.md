# Flakes & Flows: Classifying High Flow Events in Snowpack Driven Watersheds

### Members: Max Stecher, Hailey Sparks, Jesse Akes

### Summary
The goal of this project is to model and classify high flow events in Thunder Creek in Washington state. Using streamflow gauge data and nearby SNOTEL sites, we aim to determine peak over threshold flow events and what meterological conditions led to them. 

### Background

### Problem Statement/Questions/Objectives
* Are we able to model and classify events (snow, rain, or rain on snow) that cause high flows/pulses (peak over threshold events) in snowpack driven watersheds?
* What meterological conditions are required to cause these events?
* Are we able to predict peak over thresholds given these events and conditions? 

### Datasets
* [USGS Stream Gauge Data (Thunder Creek)](https://waterdata.usgs.gov/monitoring-location/12175500/#dataTypeId=continuous-00060-0&period=P7D&showMedian=false)
* [Snotel Sites](https://www.arcgis.com/apps/mapviewer/index.html?layers=719ef67bd41047bd952e497cbe6961d0)
* [Thunder Basin SNOTEL](https://wcc.sc.egov.usda.gov/nwcc/site?sitenum=817)
* [Beaver Pass SNOTEL](https://wcc.sc.egov.usda.gov/nwcc/site?sitenum=990)
* [USGS Stream Gauge Data (Big beaver Creek)](https://waterdata.usgs.gov/monitoring-location/12172000/#dataTypeId=continuous-00065-0&period=P7D&showMedian=false)

### Tools/Packages
* [Metloom](https://github.com/M3Works/metloom)
* [Data Retrieval](https://github.com/DOI-USGS/dataretrieval-python)
* [HySwap](https://github.com/DOI-USGS/hyswap)
* [Seaborn](https://seaborn.pydata.org/)
* [Scikit-Learn](https://scikit-learn.org/stable/)

### Planned Methodology
1. Identify a series of known Peak Over Threshold events on Thunder Creek (I.e. pulses that are above some typical flow value)
2. Analyze Snotel Data at Thunder Basin (above Thunder Creek Gauge) - we want to measure temperature and changes in snow water equivalent to understand what meterological conditions led to the pulse
3. Classify the pulse event (Snow, Rain on Snow, or Rain)
4. Try to apply this to historical events and understand if we can classify these high flow events

### Expected Outcome
A way to a metrologically classify high flow events in snowpack driven water sheds

### Figures and Other Info
![Puse Compared to SWE and Temp](https://github.com/user-attachments/assets/975313d4-2340-4e98-b6b6-04e78b2936f8)
![Watershed and Snotel Site Location](https://github.com/user-attachments/assets/fb5304a3-1864-4fce-9a2d-9f736e7df56a)
![High Flow Events due to Atmospheric Rivers](https://github.com/user-attachments/assets/628b471f-1047-44ea-9f15-c0719335b86b)
)


### References
[Max Temps at which snow forms by region](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2018JD030140)

