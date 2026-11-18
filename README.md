# February 2021 Texas Power Crisis Analysis

### EDS 223 Homework Assignment 4

During February 2021, severe winter storms caused widespread power grid outages in the state of Texas. This analysis explores the impacts of the power crisis on residential areas in Houston, Texas during the winter storms. The code outputs are a set of maps comparing night light intensities before and during the power crisis, a map of Houston residences that were impacted by the blackout, and a table displaying an estimate of the number of residences that lost power.

## Repository Structure:

```{r}
2021-TEXAS-BLACKOUT-ANALYSIS
│   README.md
│   2021-texas-blackout-analysis.pdf          # rendered .pdf of quarto document
│   2021-texas-blackout-analysis.qmd          # quarto document containing assignment code
└───.gitignore
     └───data                                 # folder containing data files for assignment
         └───gis_osm_buildings_a_free_1.gpkg  # Houston area houses from OpenStreetMap
         └───gis_osm_roads_free_1.gpkg        # Texas highways from OpenStreetMap
         └───VNP46A1                          # Houston area Visible Infrared Imaging Radiometer Suite (VIIRS) data
            └───VIIRS data files
```

## Data Access

Data used in this assignment were sourced with permission through the [linked data folder](https://drive.google.com/file/d/1bTk62xwOzBqWmmT791SbYbHxnCdjmBtw/view) on the [EDS 223 Homework Assignment 4 page](https://eds-223-geospatial.github.io/assignments/HW4.html).

## Data Sources 

Nighttime light raster data for the Houston, Texas area on February 7 and February 16, 2021 from NASA's Visible Infrared Imaging Radiometer Suite (VIIRS) were sourced through the [Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC)](https://ladsweb.modaps.eosdis.nasa.gov/).

Houston area highway data were from [OpenStreetMap](https://planet.openstreetmap.org/), distributed through [Geofabrik](https://download.geofabrik.de/), and prepared as a Geopackage of roads within the Houston metropolitan area.

Data for Houston residences were from [OpenStreetMap](https://planet.openstreetmap.org/), distributed through [Geofabrik](https://download.geofabrik.de/), and prepared as a Geopackage of residences within the Houston metropolitan area.


## Contributors

Author: [Priscilla Pierce](https://github.com/pr-scilla)

## References

[EDS 223: Geospatial Analysis and Remote Sensing](https://eds-223-geospatial.github.io/) Instructor: Annie Adams

The following paper was used to help inform realistic radiance values in this analysis:

Ma, Ruiqi & Zhang, Qingling & Li, D. & Liu, Shanshan & He, Tao & Zhao, Lixian. (2019). Anisotropic characteristic of artificial light at night -Systematic investigation with VIIRS DNB multi-temporal observations. Remote Sensing of Environment. 233. 10.1016/j.rse.2019.111357. 