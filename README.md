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
* [hvplot](https://github.com/holoviz/hvplot)
* [matplotlib](https://matplotlib.org/)
*[xarray](https://docs.xarray.dev/en/stable/)
### Methodology
1. **Data Processing**: Identify unimpounded watersheds that have a [SNOTEL site](https://www.nrcs.usda.gov/wps/portal/wcc/home/aboutUs/monitoringPrograms/automatedSnowMonitoring/) above a [USGS Streamgage], we used Beaver Creek SNOTEL paired with Beaver Creek streamgage and the neighboring Thrunder Basin SNOTEL paired with the Thunder Creek steamgage. **HAILEY AND JESSE ADD THINGS**
2. **Spatial Analysis and Decision Tree Development**
3. 
1. Identify a series of known Peak Over Threshold events on Thunder Creek (I.e. pulses that are above some typical flow value)
2. Analyze Snotel Data at Thunder Basin (above USGS Thunder Creek Gauge) and Beaver Creek (above USGS Beaver Creek) - we want to measure temperature and changes in snow water equivalent to understand what meterological conditions led to the pulse
3. Classify the pulse event (Snow, Rain on Snow, or Rain) "Ground Truthed" with found rain on snow events
4. Try to apply this to historical events and understand if we can classify these high flow events

### Expected Outcome
A way to a metrologically classify high flow events in snowpack driven water sheds

### Figures and Other Info

![Puse Compared to SWE and Temp](https://github.com/user-attachments/assets/975313d4-2340-4e98-b6b6-04e78b2936f8)
![Watershed and Snotel Site Location](https://github.com/user-attachments/assets/fb5304a3-1864-4fce-9a2d-9f736e7df56a)
![High Flow Events due to Atmospheric Rivers](https://github.com/user-attachments/assets/628b471f-1047-44ea-9f15-c0719335b86b)
### Figures
## Map of Sites:

### Findings
Rain on snow events are notoriously difficult to model and predict, this is a first attempt at predicting rain on snow events
### References
*Brown, D. M., et al. "Max Temps at which Snow Forms by Region." Journal of Geophysical Research: Atmospheres, vol. 124, no. 17, 2019, pp. 9516-9533, https://doi.org/10.1029/2018JD030140.

*Bormann, K. J., et al. "Snowpack Runoff." iScience, vol. 25, no. 8, 2022, Article 104821, https://doi.org/10.1016/j.isci.2022.104821.

*Lute, M. T., and D. G. Tarboton. "Mountain Rain vs. Snow." Proceedings of the International Snow Science Workshop (ISSW 2024), Montana State University, 2024, https://arc.lib.montana.edu/snow-science/objects/ISSW2024_P1.13.pdf.

*Rupp, T. S., et al. "Rain on Snow Changes in the 21st Century." Climatic Change, vol. 179, no. 1, 2024, pp. 1-15, https://doi.org/10.1007/s00382-024-07351-7.

