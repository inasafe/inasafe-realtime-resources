This folder contains template element for volcanic ash realtime

**Template version 4.8**

This template uses this data:
Analysis data (available in BtSync Folder):

| Data          | Name          | Type  | Source  |
| ------------- | ------------- | ----- | ------- |
| Hazard | Voclanic Ash | Raster | Uploaded from website |
| Population | World Population | Raster | _/common/exposure/idn_population_200m_wgs84.tif_ |
| Place and Airport | Indonesia Airport and Place | Point | _/common/exposure/idn_places_wgs84.shp_ |
| Landcover | Indonesian Landcover | Polygon | _/ash/exposure/idn_landcover_250k_wgs84.shp_ |

Information in map report sorted by order from the topmost layer:

| Data        | File Name       | Details         |
| ----------- | --------------- | --------------- |  
| Volcano Crater | _/ash/context/idn_volcano_wgs84.shp_ |
| Place and Airport | _/common/exposure/idn_places_wgs84.shp_ |
| Ash Hazard | Uploaded | 
| Hillshade terrain | _/ash/context/idn_hillshade_wgs84.tif_ |

This template has been tested with the exposure data mentioned above in the InaSAFE Desktop using the multiexposure analysis tools. The template is used when printing the pdf template for the multiexposure analysis result.
