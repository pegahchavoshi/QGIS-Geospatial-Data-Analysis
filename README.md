# QGIS Geospatial Data Analysis and Visualization


## Overview

In this project, I completed a GIS analysis project where I applied various techniques and tools to analyze geospatial data and created a detailed map.

To accomplish this, I utilized the QGIS software and explored its interface to perform a range of tasks. I employed both vector and raster data, working with diverse data formats and sources. Additionally, I installed and utilized plugins to extend the functionality of QGIS, enabling more advanced analysis and visualization options.

Throughout the project, I employed techniques such as spatial queries, overlay analysis, and geoprocessing tools to extract meaningful insights from the data. These techniques allowed me to identify spatial patterns, relationships, and trends within the dataset. I also applied data styling and symbology techniques to effectively represent the analyzed information on the map.

![Elevation_Map](https://github.com/pegahchavoshi/QGIS-Geospatial-Data-Analysis/assets/94572320/fe64f953-ac84-4478-b015-7cda96e6116b)


### Introduction

The purpose of this project is to utilize QGIS, a powerful open-source Geographic Information System (GIS) software, to conduct spatial analysis and create visualizations for urban planning. The project involves working with vector and raster data, installing plugins, styling and exporting vector files, creating maps, and exporting data in various formats.

### Objectives

1. Conduct spatial analysis to identify areas of interest and key features in the study area.
2. Visualize and analyze vector data, including polygons and points representing areas of interest and relevant infrastructure.
3. Style vector layers to enhance visual representation and extract meaningful information.
4. Incorporate OpenStreetMap data to provide context and additional information.
5. Work with raster data to visualize and analyze elevation and land cover.
6. Create maps with customized layouts and export them for presentation purposes.
7. Export data in different formats, such as shapefiles and KML, for further analysis and integration with other software.

### Setting up the Project

- I began by creating a new project in QGIS or using the shortcut (Ctrl+N).

### Working with Vector Data

To work with vector data, I imported vector data files such as "area_of_interest.shp," "hospital.shp," and "major_road.shp" into the project using the browser panel. I explored the properties of each layer, including geometry and attribute information. In order to enhance visualization, I customized the symbology of vector layers by adjusting colors, sizes, and shapes. Using the attribute table, I associated specific attributes with visual elements. To ensure optimal display, I managed the layer order, avoiding overlapping or hiding of features. Additionally, I added labels to display relevant information for each vector feature.

### Installing Plugins and Adding OpenStreetMap

I expanded the functionality of QGIS by installing additional plugins, such as the Map Services plugin. With the help of this plugin, I added OpenStreetMap data as a base layer to my project. As different data sources may have different coordinate reference systems (CRS), I adjusted the CRS to ensure proper alignment and display of the area of interest.

### Creating Shapefiles and Digitizing

To represent water bodies within a park area, I created new shapefiles. I activated the editing mode and used the digitizing tools to create polygons that covered each water body. In order to enrich the data, I added attributes such as names, locations, and numerical identifiers to the shapefile. Finally, I saved the edits and made any necessary adjustments.

### Working with Raster Data

In order to work with raster data, such as digital elevation models, I imported the relevant files into the project. I visualized the raster data using different color distributions to highlight variations. I used the identify tool to inspect elevation values for specific pixels. To focus on the area of interest, I clipped the raster data accordingly. Additionally, I created contour lines from the raster data to visualize elevation variations. To enhance the visualization, I customized the appearance of the contour lines and added labels to show elevation values.

### Exporting Data and Creating Maps

To make use of the data outside of QGIS, I exported vector data as shapefiles for further analysis and integration with other software. For visualization in Google Earth, I exported contour lines as KML files. In order to create a presentable final output, I designed a new print layout in QGIS for map composition. I added a map, legend, scale bar, north arrow, and title to the layout, customizing their style and layout as needed. Finally, I exported the final map as an image file for documentation purposes.

### Conclusion

The project using QGIS achieved excellent results in geospatial analysis and visualization. By employing various methods and tools, we successfully imported, manipulated, and analyzed vector and raster data, customized symbology, digitized shapes, and created professional maps. QGIS demonstrated its proficiency in handling geospatial data, providing valuable insights for informed decision-making in diverse domains.



































