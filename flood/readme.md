This folder contains template element for flood realtime

**Template version 4.5**

This template uses this data:
Analysis data:

| Data          | Name          | Type  | Source  |
| ------------- | ------------- | ----- | ------- |
| Hazard | Flood | Vector | Synced from PetaBencana server |
| Population | Jakarta Population | Vector | _\flood\exposure\dki_jakarta_population_wgs84.shp.shp_ |
| Aggregation | Jakarta Village Boundary | Vector | _\flood\aggregation\dki_jakarta_village_boundary.shp_ |

Information in map report sorted by order from topmost layer:

| Data        | File Name       | Details         |
| ----------- | --------------- | --------------- |  
| Displaced population with circle symbology | _/flood/aggregation/dki_jakarta_village_boundary.shp_ | This layer shows circles that represent the number of displaced people in each village. It uses the aggregation layer, but the style grabs the displaced information from the analysis result layer (aggregation summary) |
| Mask vector layer | _/flood/context/dki_jakarta_around_district_boundaries_wgs84.shp_ | This layer is to mask the other district outside Jakarta |
| Flood hazard | Flood | This layer shows where the flood is |
| District administration boundary | _/common/context/idn_admin_boundaries_wgs84.shp_ | This layer shows the Jakarta district administration boundaries |
| OSM Basemap | _/flood/context/jakarta.jpg_ | This is the basemap layer of Jakarta screen captured from the OpenStreetMap |

