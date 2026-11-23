# Extreme-weather-impacts
This repository houses the necessary materials to estimate the number of homes that likely lost power during the 2021 winter storms in Texas. 

## What's in the repository?
The data for this repository is filed under the `.gitignore`, but can be found in the section below. Code to reproduce this analysis can be found in the `extreme_weather.qmd` file. The pdf file containing the entire workflow and analysis is `extreme_weather.pdf`. The structure of the repository us as follows:

```
EDS223-HW3
└─── README.md
└─── qmd/Rmd/Proj files
└─── extreme_weather.qmd 
|   .gitignore
    └───data
         └───gis_osm_buildings_a_free_1.gpkg
         └───gis_osm_roads_free_1.gpkg
            └───VNP46A1
                └───VIIRS data files

```

## Data
The necessary data can be accessed as follows:
- [VIIRS data](https://ladsweb.modaps.eosdis.nasa.gov/)
- [TX roads](https://download.geofabrik.de/)
- [TX houses](https://planet.openstreetmap.org/)
## Authors and current contributors
[Michaela Dennis](https://github.com/michaeladennis).

## References and acknowledgements
#### Data
Index of /. (n.d.). Planet.Openstreetmap.Org. Retrieved November 22, 2026, from https://planet.openstreetmap.org/
Geofabrik download server. (n.d.). Download.Geofabrik.De. Retrieved November 22, 2026, from https://download.geofabrik.de/
LAADS DAAC. (n.d.). Ladsweb.Modaps.Eosdis.Nasa.Gov. Retrieved November 22, 2026, from https://ladsweb.modaps.eosdis.nasa.gov/