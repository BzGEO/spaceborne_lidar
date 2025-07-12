# Scripts for extracting NASA GEDI and ICESat-2 vegetation height data to shapefile format
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15870574.svg)](https://doi.org/10.5281/zenodo.15870574)

Scripts for extracting GEDI and ICESat-2 data from HDF to shapefiles

## Description: Why do I need these scripts?
*Scenario: You are a regular GIS user. You have downloaded **LARGE** HDF  (.H5) files from [NASA EarthData](https://search.earthdata.nasa.gov/search) from [GEDI](https://gedi.umd.edu/) and / or [ICESat-2](https://icesat-2.gsfc.nasa.gov/) and you just want to create shapefiles for use in [ArcGIS](https://www.esri.com/en-us/arcgis/products/arcgis-desktop/overview) or [QGIS](https://qgis.org/).* These scripts will allow you to extract out the canopy height metrics from said spaceborne LiDAR datasets.

## Disclaimer
I don't know how 🤷‍♂️ to get my [GIST](https://gist.github.com/BzGEO) files into a GitHub repo, so I have imported said files here directly. The **GEDI-to-shapefile** script was authored by [Dr. Kel Markert](https://github.com/KMarkert), while I was able to generate the **ICESat2-to-shapefile** script using some of the language used in a script from [Ryan Avery](https://github.com/rbavery).

## How to use
For the occasionally coding challenged [including myself], I have included text files that specify how to use the two scripts:

* GEDI-to-shapefile: https://github.com/BzGEO/spaceborne_lidar/blob/main/example__py_gedi.txt
* ICESat2-to-shapefile: https://github.com/BzGEO/spaceborne_lidar/blob/main/example__py_icesat2.txt.

## Source files on GIST
* Kel Markert's original **GEDI-to-shapefile** script on GIST: https://gist.github.com/KMarkert/c68ccf53260d7b775b836bf2e11e2ec3.
* Ryan B. Avery's modified **GEDI-to-shapefile** script on GIST: https://gist.github.com/rbavery/6101923f32c34e3f7db2cbbb6e282ace.
* Emil's **ICESat2-to-shapefile** script on GIST: https://gist.github.com/BzGEO/950f3db986b3513311ed42efe2395171.
