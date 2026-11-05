# Lab 3: Tile Services and Web Maps

## Independent Map README

**Purpose**
My map attempts to visualize the relationship between steep terrain of Mount Rainier and it's subsequent water runoff. I feel my map can be useful for many purposes such as for outdoor recreation planners, environmental scientists, and hikers to understand stream placement, flow paths, and watershed dynamics in relation to elevation changes across the region. 

**Study Area**
The geographic focus is the Greater Seattle and Central Puget Sound region, spanning from the Mount Rainier corridor up through King County with an upper screen bound towards Renton. The interactive camera and exported tile pyramids are restricted to zoom levels 10 through 14.

**Data Utilized**
*   **Basemap:** Mapbox Studio and OpenStreetMap.
*   **Elevation Raster:** USGS 3D Elevation Products Data; 1/3 Arc-Second Digital Elevation Model.
*   **Vector Hydrography:** USGS National Hydrography Dataset Plus High Resolution (NHDPlus HR) Flowlines (Hydrologic Unit 1711).

**Methodology**
1.  **Basemap:** I duplicated the Mapbox Light style from the guided portion, customized, and published in Mapbox Studio. It was loaded into QGIS via an XYZ connection and exported as a local tile pyramid in EPSG:3857 using QMetaTiles.
2.  **Thematic Raster:** Loaded USGS elevation data into QGIS, styled using a continuous singleband pseudocolor ramp to represent elevation heights (darker as elevation increased), and exported as a secondary transparent tile pyramid in EPSG:3857 via QMetaTiles.
3.  **Vector Data:** The USGS NHDPlus HR flowlines were clipped to the study area (mount rainier) and exported from QGIS as a WGS84 (`EPSG:4326`) GeoJSON to enable interactive line rendering and click events (popups) in the MapLibre GL JS front-end.

## Screenshots
### Guided Map (PM2.5 Interpolation)
![Screenshot of the guided PM2.5 web map](lab3/lab3-1_screenshot.png)

### Independent Map (Elevation and Hydrography)
![Screenshot of the independent elevation web map](lab3/lab3-2_screenshot.png)