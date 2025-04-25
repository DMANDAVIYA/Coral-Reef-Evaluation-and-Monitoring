## Coral Reef Evaluation and Monitoring Project (CREMP): Long-Term Assessment and Conservation Strategies for Florida’s Coral Reefs (1996–2023)

Overview
This repository contains a Jupyter notebook (coralp.ipynb) for analyzing 2023 data from the Coral Reef Evaluation and Monitoring Project (CREMP), which monitors Florida's coral reefs. The notebook loads CSV files, inspects data, and visualizes temperature and coral cover spatially.

The Coral Reef Evaluation and Monitoring Project (CREMP) monitors the status and trends of selected coral reefs along Florida’s Coral Reef from Martin County to the Dry Tortugas, excluding Biscayne National Park and the Marquesas. CREMP’s success in documenting both short- and long-term changes in benthic communities is due to the program’s broad spatial coverage, robust sampling design, tenure, and the program’s willingness to consistently adapt its monitoring protocols to address management priorities. CREMP is split into three main regions (see map). CREMP in the Florida Keys was initiated in 1996 and monitors 40 reefs between Carysfort Reef off Key Largo and Sand Key in Key West. CREMP in the Dry Tortugas was established in 1999 and monitors 11 reefs in Dry Tortugas National Park and one reef in Tortugas Ecological Reserve North. CREMP in Southeast Florida (SECREMP) started in 2003 and monitors 22 reef sites between Martin County and the northern boundary of Biscayne National Park. Collectively, the spatial effort for monitoring across the three regions includes >70 sites under the CREMP framework along Florida’s Coral Reef.  

The Coral Reef Evaluation and Monitoring Project (CREMP) in the Florida Keys is managed by the Corals Research Program and the Fish and Wildlife Research Institute and funded by the Environmental Protection Agency as part of the Florida Keys National Marine Sanctuary Water Quality Protection Program. This Sanctuary-wide project is documenting the status of reef habitats at 40 reef sites located within 5 of the 9 EPA Water Quality Segments in the Florida Keys National Marine Sanctuary. Over the duration of the project, the randomly located reefs in this project may show no net decline. Alternatively, some or all the reefs may show a net decline. Data for each successive sampling year will be compared with prior year's data to obtain a broader understanding of the dynamics of the FKNMS coral reef system. As the coral reef monitoring is integrated with the seagrass and water quality programs, the results can be used to focus research on determining causality and can be used to inform and evaluate management decisions.

## Credits (Attribution):
Florida Fish and Wildlife Conservation Commission - Fish and Wildlife Research Institute and the CREMP Team and Collaborators. The Coral Reef Evaluation and Monitoring Project (CREMP) in the Florida Keys is managed by the Corals Research Program and the Fish and Wildlife Research Institute and funded by the Environmental Protection Agency as part of the Florida Keys National Marine Sanctuary Water Quality Protection Program.

## Operation and Analysis done

1.	Average Stony Coral % Cover Over Time (All Stations)
2.	Stony Coral percent over time
3.	Stony Coral Species Richness over time
4.	Octoral density over time
5.	Living Tissue Area across stations 
6.	Spatial Patterns Sample:
7.	Octoral Density vs Water temperature
8.	Stony Coral density vs. species richness
9.	Average coral density over time by subregion 
10.	Top 10 coral species composition by subregion 
11.	Correlation between coral and health factors
12.	Forecast of average coral % cover 
13.	Coral disease count by station 
14.	Coral vs Microalgae cover over time (sanctuary-wide)
15.	OCtoral mean vs height of temperature
16.	Top 10 sites with highest recent coral mobility
17.	Stony coral cover by station (folium)
18.	Stations clusters based on coral cover & richness
19.	Lagged correlation: Last year’s temp vs current coral cover
20.	Forecast: Macroalgae % Cover Over Time
21.	Anomaly detection: Coral cover outliers 
22.	TOP EARLY WARNING STATIONS:
23.	Top 10 Early-Warning Reef Sites (Risk Score)
24.	Top 10 healthiest reef
25.	Top 10 composite health score
26.	Species composition flow (Start vs End year)
27.	Lagged temperature vs coral cover
28.	Top 10 Declining Coral Species by Cover Trend
29.	Coral disease heatmap by subregion
30.	Technical Interpretation of Reef Recovery Predictor Performance
31.	Potential Coral Heat Stress Map (folium)
32.	Station timeline plot
33.	Spatial distribution of temperature and coral cover
34. Stony coral percent cover over time by Subregions

## Document

Check the document for more and extensive detail about the project.

## Requirements

Python 3.8+
Jupyter Notebook
Libraries: pandas, matplotlib, seaborn, geopandas, folium, esda

Setup
Clone the repo:
git clone https://github.com/DMANDAVIYA/Coral-Reef-Evaluation-and-Monitoring.git

Install dependencies:
pip install pandas matplotlib seaborn geopandas esda folium


Download CREMP 2023 CSV files https://www.arcgis.com/home/item.html?id=2ab2e706c83d4247855f8e4e689c7cba


## Usage

Open Jupyter Notebook:
jupyter notebook

Open coralp.ipynb and update the data path in the second cell:
directory = r"path/to/your/CREMP_CSV_files"


Run the cells:

Cell 1: Imports libraries.
Cell 2: Loads CSV files and shows column names/types.
Cell 3: Plots temperature and coral cover maps (requires geopandas).


## Data

Terms of Use

FWC-FWRI and collaborators must be credited. The Coral Reef Evaluation and Monitoring Project (CREMP) in the Florida Keys is managed by the Corals Research Program and the Fish and Wildlife Research Institute and funded by the Environmental Protection Agency as part of the Florida Keys National Marine Sanctuary Water Quality Protection Program. This is not a survey data set and should not be utilized as such. These data are not to be used for navigation.
The notebook uses 2023 CREMP CSV files, including:


## Contact

Author: Dhruvil Mandaviya
Email: dmandaviya0369@mail.com
GitHub: DMANDAVIYA

