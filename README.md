# Colorado Broadband Provider Map

## Table of Contents

- [Lesson 02: Open Source GIS and Data Management Tools – Introduction to QGIS and PostGIS](#lesson-02-open-source-gis-and-data-management-tools--introduction-to-qgis-and-postgis)
    - [Table of Contents](#table-of-contents)
    - [Overview](#overview)
    - [Data files](#data-files)

## Overview
Interactive Colorado Broadband Provider map utilizing MapBox GL API.  Interactive Popup and dynamic layer symbology based on zoom level.

## Data Sources

* *US Census Block Polygons*
	* Shapefile of US Census Block Polygons from the 2010 US Census. The source of this data is [US Census Bureau Tigerline Data](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html).
* *Fixed Broadband Deployment Date from FCC Form 477*
	* CSV containing all fixed broadband provider 477 submisions from June 2018. The source of this data is [Federal Communications Commission Form 477 Deployment Data](https://www.fcc.gov/general/broadband-deployment-data-fcc-form-477).