# EJ-AQ
Cumulative air pollution indicators for Vancouver, Toronto, Montreal

## Cumulative air pollution indicators highlight unique patterns of injustice in urban Canada: Data Files
### Amanda Giang, Kaitlin Castellani, August 28 2020


Shapefiles for each city (Toronto, Vancouver, Montreal) with air pollution and demographic data at the Dissemination Area (DA) level are included in this respository. Please see Giang and Castellani (2020) for citations for all data sources. 

Variables for each shapefile (city.shp) are as follows:

* **DAUID**: Unique identifier for each DA
* **NO2**: 2012 NO2 concentration (annual average ppb)
* **O3**: 2012 O3 concentration (annual average ppb)
* **SO2**: 2012 SO2 concentration (annual average ppb)
* **PM**: 2012 PM2.5 concentration (annual average ug/m3)
* **MFS**: 2016 Material Deprivation Score 
* **SFS**: 2016 Social Deprivation Score
* **VisMin**: 2016 Visible Minority Population 
* **VisMinp**: Proportion Visible Minority Population
* **NonVisMin**: Non-Visible Minority Population
* **Pop_VisMin**: Total population for VisMin census variable (differs from Tot Pop, because inferred from long-form census)
* ... same pattern for other census variables
* **TotPop**: Total population (from short-form census, 100% coverage)
* **ratioNO2**: pollutant concentration/benchmark concentration 
* **normPM**: normalized pollutant concentration
* **Bin_Reg**: Binary Cumulative Hazard Index
* **Add**: Additive Cumulative Hazard Index
* **Mult**: Multiplicative Cumulative Hazard Index

Please attribute the use of this data to:

Giang A, Castellani K. 2020. Data Files: Cumulative air pollution indicators highlight unique patterns of injustice in urban Canada

Underlying air pollution data should be attributed to: 

We thank the Canadian Urban Environmental Health Research Consortium ([CANUE](canue.ca)) and air quality scientists for the underlying air pollution data sets used in this work: PM2.5 data were provided by the Atmospheric Composition Analysis Group at Dalhousie University, Halifax, Canada (http://fizz.phys.dal.ca/~atmos/martin/?page_id=140). Nitrogen dioxide data used by CANUE were provided by: Dr. Perry Hystad, Oregon State University. Regional adjustment factors were developed by Dr. Lauren Pinault, Environmental Health Epidemiologist, Statistics Canada, and Dr. Richard Burnett, Senior Research Scientist, Health Canada, using data compiled by Dr. Hwashin Shin, Research Scientist, Health Canada, from the National Air Pollution Surveillance monitoring network. The authors acknowledge Environment and Climate Change Canada for the provision of ground-level ozone data accessed via CANUE. All air pollution data indexed to DMTI Spatial Inc. postal codes were provided by CANUE. 

Boys B L, Martin R V, Van Donkelaar A, MacDonell R J, Hsu N C, Cooper M J, Yantosca R M, Lu Z, Streets D G, Zhang Q and Wang S W 2014 Environmental Science and Technology 48 11109–11118 

Van Donkelaar A, Martin R V, Spurr R J and Burnett R T 2015 Environmental Science and Technology 49 10482–10491

Environment and Climate Change Canada 2017 Data Files: GEMMACH Ground- Level-O3 NA 2010.nc to GEMMACH Ground-Level O3 NA 2015.nc inclusive

Robichaud A and M ́enard R 2014 Multi-year objective analyses of warm season ground-level ozone and PM2.5 over North America using real-time observations and Canadian operational air quality models vol 14

Robichaud A, M ́enard R, Za ̈ıtseva Y and Anselmo D 2016 Air Quality, Atmosphere and Health 9 743–759

Hystad P, Setton E, Cervantes A, Poplawski K, Hystad P, Settori E, Cervantes A, Poplawski K, Deschenes S, Brauer M, Donkelaar A V, Lamsal L, Martin R, Jerrett M and Demers P 2011 Environmental Health Perspectives 119 1123–1129

Weichenthal S, Pinault L L and Burnett R T 2017 Scientific Reports 7 1–10 ISSN 20452322 URL http://dx.doi.org/10.1038/s41598-017-16770-y

Environment and Climate Change Canada 2017 Data files: OMI Ground- Level SO2 NA 2005.nc to OMI Ground-Level SO2 NA 2015.nc inclusive

McLinden C A, Fioletov V, Boersma K F, Kharol S K, Krotkov N, Lamsal L, Makar P A, Martin R V, Veefkind J P and Yang K 2014 Atmospheric Chemistry and Physics 14 3637–3656

Kharol S K, McLinden C A, Sioris C E, Shephard M M, Fioletov V, Van Donkelaar A, Philip S and Martin R V 2017 Atmospheric Chemistry and Physics 17 5921–5929

Institut national de sant ́e publique du Qu ́ebec (INSPQ) from 1991 1996 2001 2006 2011 and 2016 Canadian Census data 2019 Index of material and social deprivation compiled by the Bureau d’information et d’ ́etudes en sant ́e des populations (BIESP). URL https://www.inspq.qc.ca/en/ information-management-and-analysis/deprivation-index
