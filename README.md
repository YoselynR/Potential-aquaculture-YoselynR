# Geospatial analysis - Potential aquaculture 
*This is a project repository for UCSB's MEDS program, EDS 223 class.*
### Author: Yos Ramirez

## About
The Home Owners' Loan Corporation (HOLC) grades, created in the 1930s, categorized neighborhoods based on perceived safety for real estate investment. This practice led to the "redlining" of predominantly Black and Latino neighborhoods. Using geographic data (spatial features), maps were generated to visualize the distribution of HOLC grades across LA County and how these grades correlate with specific environmental variables, such as particulate matter exposure, low life expectancy, and low income. These redlined neighborhoods still exhibit enduring socioeconomic and environmental disadvantages. Biodiversity data was examined to see if redlining had any correlation with bird diversity in LA.

## Purpose
The goal of this project is to explore the intersection of historical redlining practices and contemporary environmental and biodiversity challenges in the Los Angeles (LA) region, specifically focusing on the relationship between redlined neighborhoods, environmental justice (EJ), and biodiversity. 

## Highlights
- The map revealed that grade C neighborhoods (the most common in the region) are concentrated in certain parts of LA, with grade D areas less prevalent than initially assumed.
- Boxplots demonstrated how environmental conditions (like exposure to particulate matter and low life expectancy) worsen as HOLC grades increase from A to D, especially in grade D neighborhoods.
- The summary table confirmed the increasing environmental disadvantages for communities with worse HOLC grades, suggesting a legacy of systemic inequality.
- A spatial join was performed between the HOLC data and the biodiversity dataset, specifically focusing on bird observations from 2022, which showed bird observation counts were higher in grade C neighborhoods.

## Summary/Limitations
The correlation between environmental conditions (e.g., particulate matter and life expectancy) and HOLC grades suggests that neighborhoods with lower grades (D and C) may suffer from more environmental hazards, which could correlate with a decrease in biodiversity. However, no direct correlation between redlining and bird observations was found in this preliminary analysis. Further research is needed, particularly to account for neighborhood size and other confounding factors. The relationship between HOLC grades and biodiversity was complex, with redlined areas showing more bird observations, potentially due to the higher number of grade C neighborhoods in LA. The presence of a high number of grade C neighborhoods may explain the higher count of observations in these areas, but further analysis considering neighborhood size, bird species, and other factors would be necessary to draw stronger conclusions. 

The analysis supports the hypothesis that neighborhoods with poorer HOLC grades are more likely to experience worse environmental conditions, which could contribute to health disparities and reduce the quality of life in these communities. While bird observations are more frequent in redlined neighborhoods, the connection between these observations and redlining is not entirely clear, and further analysis considering more ecological and socio-environmental factors would be valuable. This project underscores the importance of examining historical practices, such as redlining, in understanding present-day environmental injustices and biodiversity issues. While some trends are clear, further research is needed to fully understand the complex relationship between these factors.

## Data
The analysis incorporates three primary datasets:
HOLC Grades: Historical redlining data for Los Angeles.
EJScreen Data: A tool developed by the EPA to assess environmental and demographic conditions in U.S. communities.
Biodiversity Data: Bird observation data from the Global Biodiversity Information Facility (GBIF) for LA County.
## References

## Repository organization
```
Potential-aquaculture-YoselynR
├── README.md
├── Potential-aquaculture-YoselynR.html
├── Potential-aquaculture-YoselynR.qmd
├── .gitignore
├── LICENSE
├── Potential-aquaculture-YoselynR_files
|   ├── .csv
└── images
    │   .jpg
```
