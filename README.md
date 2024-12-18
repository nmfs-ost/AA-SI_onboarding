# Active Acoustic Strategic Initiative (AA-SI) Onboarding

## Welcome!
Are you new to the AA-SI or just want a refresher? Here is the site for you!  

## Background
The goals of the Active Acoustics Strategic Initiative (AA-SI) include organizing and standardizing multi-frequency and wide-bandwidth echosounder data to enable efficient data processing and analysis. This repository houses useful background information on how active acoustics are used to study fish and zooplankton, the types of equipment and data formats commonly employed, and requirements for data standarization. 

## AA-SI GitHub Site
Find out more about the AA-SI GitHub site [here](https://github.com/nmfs-ost/AA-SI_onboarding/tree/main/GitHub).

## Google Work Space
Find out more about the AA-SI Google work space [here](https://github.com/nmfs-ost/AA-SI_onboarding/tree/main/GoogleCloudWorkspace).

## Data Collection: Instrumentation
Find out more about the echosounders that NOAA Fisheries has used to collect active acoustic data over the past several decades [here](https://github.com/nmfs-ost/AA-SI_onboarding/blob/main/Instruments/README.md).

## Data Formats
The scientific [echosounders](https://github.com/nmfs-ost/AA-SI_onboarding/tree/main/Instruments) record data to manufacturer-specified binary formats. Data formats for the Kongsberg EK echosounders have changed with each model and within models. While these formats are proprietary to the manufacturer, the formats are published for anyone to write custom software to read the data files. Almost all fisheries institutions that use the active acoustic data have custom-built software to read, process, and analyze the data, and in addition, many use a commercial software package, [Echoview](https://echoview.com/) to read, process, and analyze the data. 
  
Over the years, this process has worked for individual institutions, but as the active acoustic data have become public through NOAA's National Center for Environmental Information [NCEI](https://www.ncei.noaa.gov/products/water-column-sonar-data) or other portals, the ability for those outside of the fisheries institutions to utilize the data for purposes other than fisheries single-species stock assessments is quite arduous to impossible. To broaden the utility of active acoustic data, the fisheries acoustics community has developed open data formats so that the data can be read by any software language. Early attempts included the [HAC](https://ices-library.figshare.com/articles/report/Description_of_the_ICES_HAC_Standard_Data_Exchange_Format_Version_1_60/18624254?file=33403313) format, but have mostly been supplanted by [netCDF4](https://www.unidata.ucar.edu/software/netcdf/conventions.html). The AA-SI will be using the netCDF4 convention.  

### netCDF4 Format
Find out more about the AA-SI's use of [netCDF4 format]().

# Disclaimer
This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.
