# Houston Winter Blackout

### Mapping Power Outages from the February 2021 Winter Storm in Houston, Texas

**Author** William Mullins

### About

This repository contains a quarto markdown document of my analysis on the opower outages in Houston during the 2021 winter storm.

### Data Descriptions:

-   VNP46A1: Raster data of night sky radiance in Houston, Texas during the winter storm.

-   gis_osm_buildings_a_free_1.gpkg: Open streetmap data on buildings

-   gis_osm_roads_free_1.gpkg: Open street map data on Roads. Used to identify highways in the Houston Area.

-   ACS_2019_5YR_TRACT_48_TEXAS.gdb: Geodatabase containing socioeconomic information for homes in the United states. Data was collected by the U.S. Census Bureau’s American Community Survey.

### Repo structure:

*Data Folder Was Not Pushed*

```         
houston_blackout_impact
└───README.md
└─── houston_blackout.qmd 
└───.gitignore
    └───data
        └───gis_osm_buildings_a_free_1.gpkg
        └───gis_osm_roads_free_1.gpkg
        └───ACS_2019_5YR_TRACT_48_TEXAS.gdb
            └───census tract gdb files
        └───VNP46A1
            └───VIIRS data files
```

### References:

-   NASA Earth Observing System Data and Information System (EOSDIS). (2021). VIIRS Day/Night Band Nighttime Lights, Version 1. NASA Earthdata. <https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms/viirs-i-band-nighttime-lights> Accessed: November 10, 2025.

-   U.S. Census Bureau – American Community Survey (ACS) U.S. Census Bureau. (2021). 2019 ACS 5-Year Estimates: Tract 48. American Community Survey. <https://www.census.gov/programs-surveys/acs> Accessed: November 10, 2025.
