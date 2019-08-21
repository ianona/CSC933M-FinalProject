## README
1. Place all required datasets and shapefiles into DSDATA
   - Rename files accordingly (see filenames below)
2. Run the notebook from top to bottom

Required datasets
Link for Fire Incident 2012-2016 Statistics dataset: https://data.gov.ph/dataset/bfp-nationwide-fire-incidents-statistics-cy-2012-2016
<br>Link for BFP & LGE Firetrucks dataset: https://data.gov.ph/dataset/bureau-fire-protection-bfp-and-local-government-unit-lgu-fire-trucks
<br>Link for IRA Dependency by Province dataset: https://data.gov.ph/dataset/internal-revenue-allotment-dependency
<br>Philippine shapefile: http://philgis.org/country-basemaps/country-boundary
<br>Metro Manila shapefile: http://philgis.org/province-page/metro-manila

Directory and Filenames: DSDATA/
BFP_FIreIncidents2012-2016.csv
bfp_firetrucks.csv
2009-2014_irad_by_province.csv

MetroManilaBoundaries/MetroManilaBoundaries.shp
gadm36_PHL_shp/gadm36_PHL_2.shp

* shapefiles used in the project were retrieved from Canvas, links placed above may not be the exact shape file used since the Canvas link could not be placed
* some cells may take longer to run due to the volume of data (especially the cells that merge shapes from the shapefile)
* colors used in the bar chart for Mean Number of Incidents (Log scale) may differ across browsers (Firefox on Windows generates different colors, Chrome on Mac generates the same default color)