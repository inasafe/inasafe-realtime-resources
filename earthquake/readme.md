This folder contains template element for earthquake realtime

**Template version 4.4**

This template uses this data:
Analysis data:

| Data          | Name          | Type  | Source  |
| ------------- | ------------- | ----- | ------- |
| Hazard | Earthquake | Raster | Converted from grid.xml synced from BMKG server |
| Population | World Population | Raster | _/common/exposure/idn_population_200m_wgs84.tif_ |
| Place | Indonesia cities | Point | _/common/exposure/idn_places_wgs84.shp_ |


Information in map report sorted by order from topmost layer:

| Data        | File Name       | Details         |
| ----------- | --------------- | --------------- | 
| City Point |  _/common/exposure/idn_places_wgs84.shp_ | This layer shows the place information |
| MMI contour | converted from analysis | This layer shows the grid MMI converted from the analysis result |
| District administration boundary | _	/common/context/idn_admin_boundaries_wgs84.shp_ | This layer shows the Jakarta district administration boundaries |
| Population Layer | _/common/exposure/idn_population_200m_wgs84.tif_ | This layer shows the Indonesian population |

This is template has been tested with the exposure data mentioned above in the InaSAFE Desktop using the multiexposure analysis tools. The template is used when printing the pdf template for the multiexposure analysis result.
