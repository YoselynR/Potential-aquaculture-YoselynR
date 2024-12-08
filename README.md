# Geospatial analysis - Potential aquaculture 
*This is a project repository for UCSB's MEDS program, EDS 223 class.*
### Author: Yos Ramirez

## About

This project is designed to analyze and visualize the suitability of locations for marine aquaculture based on environmental parameters such as Sea Surface Temperature (SST) and bathymetry (depth). The focus is on determining regions along the U.S. West Coast that are most suitable for aquaculture, specifically for species like oysters and squid. 

SST and Depth Suitability: For each species, temperature and depth preferences were defined:

Oysters: Suitable SST between 11°C and 30°C, depth between 0m and 70m.

Squid: Suitable SST between 8°C and 13°C, depth between 20m and 180m.

## Purpose
A general function, calculate_suitable_eez_area(), was developed to allow for similar analyses for different species, temperature/depth preferences, and time periods. This makes the workflow scalable and adaptable to other marine species and different geographic regions. The project highlights the utility of spatial data processing and visualization techniques in determining aquaculture potential, helping stakeholders prioritize areas for farming specific species. The mapping clearly demonstrates the geographic variation in aquaculture suitability, offering valuable insights for marine resource management and aquaculture planning. The approach can be extended to other species or regions, making it a flexible tool for marine resource management and aquaculture development.

## Highlights
- Key libraries like raster, sp, sf, terra, and tmap were used to load, manipulate, and visualize spatial data.
- The spatial data was reprojected to UTM Zone 10N for uniformity in measurements (in meters), ensuring compatibility between datasets.
- The mean SST was computed over a specified period (2008-2012), converted from Kelvin to Celsius, and then resampled to match the bathymetry raster.
- Suitable locations for aquaculture were determined by combining both suitability layers (SST and bathymetry) through an overlay operation, where only areas meeting both criteria were considered suitable.
- The suitability map was rasterized to match the EEZ shapefile, allowing for analysis by region (e.g., Washington, California).
- The total suitable area for aquaculture was computed by region.
- The tmap package was used to create visually appealing maps that highlight the suitable areas for each species within each EEZ.
- The maps include color-coded representations of total suitable area per EEZ region.

## Data
The project integrates multiple spatial datasets, including bathymetry and SST rasters, and EEZ (Exclusive Economic Zone) shapefiles.

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
