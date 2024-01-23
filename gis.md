https://ocw.mit.edu/courses/res-str-001-geographic-information-system-gis-tutorial-january-iap-2022/pages/gis-level-1/
## Geographic Information System
A system for capturing, storing, checking, integrating, manipulating, analyzing and displaying spatial data.

![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/063f3cfb-3364-4d81-9a5d-0826c4886384)

## Theoretical Overview
GIS recreates real world spatial data as digitized themed data “layers” (e.g. locations, boundaries, infrastructure, socioeconomic hydrology, land use/cover) assembled in any combination and overlaid for analysis

## SOFTWARE
### Types of GIS & Mapping Software

| Type | Analysis Power | Example(s) |
|--|--|--|
| Geobrowser | Weak (mainly only to display data) | Google Maps, Google Earth, Apple Maps, Waze, etc. |
| Web-based | Medium (able to upload additional data, customize display, and perform basic analyses) | Carto, ArcGIS Online, Mapbox, Google MyMaps, etc. |
| Desktop | Strong (installed locally, provides full control of map creation, and perform advanced analyses) | ArcGIS Pro, QGIS |

### Which desktop software should you use today?
| ArcGIS Pro (by ESRI)  | QGIS |
|--|--|
| Commercial software (expensive to purchase) | Free, open-source tool |
| Only runs on Windows | Runs on any operating system |
| Larger program – can run slowly on some computers | Smaller program that will not affect performance of your computer |
| Full set of GIS functions and tools | Many available tools, but lacking some for specific functions, such as network analysis (i.e. routing) and spatial statistics |
| Integration with ArcGIS Online | Basic tutorials by QGIS developers and users |
| Fully developed training program (online modules, written tutorials, MOOCs) | Tools can be developed by anyone so performance and documentation is inconsistent. |
| Comprehensive support (direct support from ESRI, documentation for every tool) | Support via forums |

## GIS APPLICATIONS
### View Imagery
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/438dcd17-df45-4ba7-ba3d-4a6791e5e1b2)

### Create 3D models 
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/7a2d4f34-6955-45e5-a244-53bd99ffbff5)

### Conduct Analysis
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/0cca3589-03b8-429b-be41-f935ab67229f)

## UNDERSTANDING MAPS & DATA
### MAPS & DATA: SPATIAL DATA TYPES
#### Geospatial Data Types
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/aee56d7f-9d82-4085-8882-14f72b74ca98)
#### Data Types: Vector versus Raster
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/8deff8ba-5554-423a-8cc8-ab4328a3cf42)
#### Data Types: Vector examples
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/ac8b74cc-d1e9-4c2b-a2fa-8db4593c834b)
#### Data Types: Vector mapping
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/e05f55a5-ea22-4bf6-9f9c-d31ed90c1a64)
#### Data Types: Vector mapping
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/b3aa7ce0-da67-4c63-9ec8-afa8321eac62)
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/71307e5a-4de3-46c6-b271-2cf36b51ab2f)
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/5d6701a0-f128-4367-b810-a262a4ff92cf)
#### Data Types: Vector file formats
- The shapefile is the most common vector file format.
- “A” shapefile is actually a collection of several different files with different extensions.
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/879454d5-85b4-4ced-b14f-8cb71ea0cc10)
#### Data Types: Raster
Raster data includes aerial photographs, digital elevation models, and scanned maps.
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/d7baa51e-781c-42f1-b57c-6a9b4975b419)
#### Data Types: Raster mapping
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/50e3153f-1dcb-433d-90ed-fec9761adb3c)
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/8da60d0a-a470-44a7-8ece-fbd6b1489022)
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/4bb5ff71-ce9c-4de2-9c33-98e7c39a7bb2)
#### Data Types: Raster file formats
There are many different raster file extensions, including common image formats. 
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/edd8f524-d034-4cf7-bacf-3855f6df1abd)
#### Data Types: Tabular
1. Joining
- Use a shared unique identifier (GEOID, name, etc.) to match up tabular data to the spatial data’s attribute table.
2. Geocoding
- Use lat/lon coordinates in table to plot as points on map
- Use addresses to plot locations based on a street network
#### Data Types: Tabular file formats
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/7f4bc981-6ddd-4c07-b222-b19ecd070f87)
### Geodatabases
 - ESRI/ArcGIS storage system
 - A collection of geographic datasets of various types held in a common file system folder
 - Advantages: larger files size limits, faster processing time when using analysis tools
 - Disadvantages: can only be opened in ESRI software
 - Learn more about [using geodatabases in Pro](https://pro.arcgis.com/en/pro-app/latest/help/data/geodatabases/overview/what-is-a-geodatabase-.htm).
### Other data formats
GIS can import and convert data produced in other formats:
- KML / KMZ files (Google Earth)
- DXF / DWG (CAD)
- NetCDF (scientific data)
- LAS (Lidar)
- GPX (GPS units)
- Geojson 
GIS software can export many formats:
- Adobe Illustrator
- KML
- CAD
- TIF
- JPG
### Common Associated Workflows
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/9adc98b2-1a38-464f-af74-ec01bf439daf)

## MAPS & DATA: CHARACTERISTICS OF SPATIAL DATA
### GENERALIZATION
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/06abe3b7-7db5-415b-bc05-54b51f4aabdc)
- The most detailed data available is not suitable for all purposes (or often a manageable file size)
- e.g. resolution of coastline data for this map is scale dependent: Red for county map and Blue for town map.
### Abstraction
The process of reducing data from its complete state to what is necessary for use and presentation
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/ae6ca2ae-7b2f-46ec-a584-feb031b0753c)
### Spatial Resolution/Scale
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/b6182b5f-f70e-4255-aae6-453ee3fed846)
Suitable data geometry is dependent on scale: e.g. roads are polygons at local scale but lines at national scale
### Temporal Resolution
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/23e361a8-b5b5-44a3-9541-e311c18996d3)
### Searching for Spatial Data
- Look in general GIS data repositories
- Search the internet
  - Include “gis”, or “data” in the search terms
  - Search by location and/or topic
- Search for country statistical agencies or open data sites (large cities often have their own open data portals as well)
- Contact GIS departments, universities, or researchers in your area of interest.
- Search for articles on your topic and look for the sources of the data.
### Repositories and Websites
- http://libguides.mit.edu/gis
- http://geodata.mit.edu/
- http://openstreetmap.org/

## MAPS & DATA: METADATA 
What is Metadata?
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/126ae801-d7ac-4ae4-acf0-8a01711c61e7)
### Metadata Examples
- MassGIS: https://www.mass.gov/info-details/massgis-datamarine-beaches
- GeoWeb: geodata.mit.edu/catalog/mitw37ehgh6nvl4w
- City of Boston: https://data.boston.gov/dataset/trafficsignals
## MAKING GREAT MAPS: DATA VISUALIZATION PRINCIPLES
### Making Great Maps
- Cartography is the art and science of making maps
- Maps are always simplifications of reality, which makes them helpful when making decisions or explaining patterns
- Maps are designed by people (who have intentions), so we have to create them responsibly
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/71479963-5868-4a63-8b97-dd56e486643b)
### Map Design Process
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/9c0bdfb8-5aeb-4d7a-8aa2-55c9822b5d79)
### Vector Symbolization
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/a1a857dc-2dcb-46cc-a394-4e8be14bf74b)
[Colorbrewer](https://colorbrewer2.org/) provides accessible color options.
### Raster Symbolization
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/c0f80d22-c0d1-4415-baba-060891199c42)
### Choosing Color Tips
Match the type of data to the type of color scheme:
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/1737af67-deb4-4063-b483-660469cde9aa)
### Qualitative Color Example
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/ae692e1d-21aa-4810-97cf-1d7bba7eb640)
### Sequential Color Example
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/b1163afe-1098-4978-bcba-94abae853303)
### Diverging Color Example
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/7389bd9f-1c9d-4ec4-9edd-7fbaf3dd499b)
### Commonly used map type: Choropleth
These use different shading and coloring to display the quantity or value in defined areas.
![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/cb4f5e41-aee1-41f2-ac0b-c392d8183df7)
### Choropleth map choices
1. Number of Classes
  - Aggregates data for display
  - More classes = more variation (best to have no more than 7)
    ![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/e5b07e3b-bc9e-4316-859c-4f209b5563fa)

2. Classification Method
  - Data classification is how data is arranged into separate classes.
  - Major types
     - Equal Intervals
     - Quantile (Equal Count)
     - Natural Breaks
     - Defined Intervals

### Classification Methods
- Equal Interval = classes have equal ranges
- Quantile = classes have equal counts
- Natural Breaks = optimizes class variation
- Manual = you define classes

![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/a0ba28cc-ea37-4dc9-aeb3-db45f85c951f)

### Map Layout Design Example
**Overview**
- Map layout design is about developing a balanced arrangement
- Maps, title, legend, scale bar, labels, etc. all need relative positioning & sizing
- Goal is to design the map layout to support your design questions
  - Who wants the map
  - Where will it be seen
  - What is its purpose

![Screenshot from 2024-01-23 23-41-02](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/ef135570-68b1-4c5b-afd5-0d4a15a3f9dd)

**Tips**
- Inset/locator maps are often placed in the top/bottom corners (e.g. continent view top left and zoomed view in bottom right).
- Main map often placed in center (usually largest & most detailed).
- Legend is tucked into the main map for easy comparison with the data.
- Scale bars and north arrows shouldn’t be a distraction from the main map.
- Sources should run along the bottom.

![image](https://github.com/opentechcommunity/gis-and-mapping/assets/103439622/41774b47-5981-4466-8cde-e195d97acee0)


