# Kentucky's National Register listed Civil War Sites
This map presents some of Kentucky's National Register listed Civil War sites. The locations are in the form of points and polygons. The points represent buildings, objects, sites, and structures, while the polygons represent buildings, districts, sites, and structures. 

The map is available [here](/Map/index.html) and as a [full-screen version](/Map/map.html).

## Data
The data used for this map was extracted from the [National Register of Historic Places](https://www.nps.gov/subjects/nationalregister/index.htm), [ESRI ArcGIS geodatabase](https://catalog.data.gov/dataset/national-register-of-historic-places-1ab90) using [QGIS](https://www.qgis.org) version 3.38.3 for use with [MapBox](https://www.mapbox.com).
The  extracted data is available here:
  + [Polygons](/Data/NR_KY_CW_Polygon.geojson.zip)
  + [Points](/Data/NR_KY_CW_Points.geojson.zip)

Please be aware that the dataset may contain spatial errors. For more information, see the _"Can you explain why a feature looks ‘odd’ in the GIS dataset?"_ explanation found in the [FAQ](https://irma.nps.gov/DataStore/DownloadFile/706729?Reference=2305305) for the geodatabase.

## Map Style, Font, and Symbols Used
I wanted to give this map an antique look. The style is based on the [vintage map style](https://blog.mapbox.com/designing-the-vintage-style-in-mapbox-studio-9da4aa2a627f) developed by Amy Lee Walton and available from this [GitHub](https://github.com/mapbox/mapbox-gl-vintage-style) page. 

The font used for the map is the [Fredericka the Great](https://fonts.google.com/specimen/Fredericka+the+Great) font.

The point symbol used is based on the National Park Service [Map Symbols & Patterns for NPS Maps](https://www.nps.gov/subjects/gisandmapping/map-symbols-patterns-for-nps-maps.htm), which is available at this [GitHub](https://github.com/northrivergeo/NPS_Map_Symbols?tab=readme-ov-file) page. The monument symbol can be downloaded [here](/Fonts_Styles/monument_light.svg). 

<img src="/Fonts_Styles/monument_light.svg" alt="monument" width="100">

While the [vintage map style](https://blog.mapbox.com/designing-the-vintage-style-in-mapbox-studio-9da4aa2a627f) worked well as a base map, I needed an additional map style for the polygon data so I created a darker version of the texture-dktan_64.svg fill. The modified texture style can be downloaded from [here](/Fonts_Styles/texture-dktan_64_2.svg).

<img src="/Fonts_Styles/texture-dktan_64_2.svg" alt="texture-dktan_64_2.svg" width="100">

## County Boundary and Lable Points
[Kentucky county line](https://opengisdata.ky.gov/datasets/0e6c3b4b630a44b495ffd72196dec3b8_0/explore?location=37.577806%2C-85.794337%2C5.86) and [Kentucky county polygon](https://opengisdata.ky.gov/datasets/ad52760b298b4f2b8879233fecd1acd1_0/explore) data was obtained from the [KyGovMaps Open Data Portal](https://opengisdata.ky.gov/) and processed using [QGIS](https://www.qgis.org) version 3.38.3 for use with [MapBox](https://www.mapbox.com). The [Kentucky County Polygons](https://opengisdata.ky.gov/datasets/ad52760b298b4f2b8879233fecd1acd1_0/explore) was used to create a label center for each county. 




This site was built using [GitHub Pages](https://pages.github.com/).
