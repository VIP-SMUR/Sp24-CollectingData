This repository serves as a basic example of how to use packages such as geopandas, folium, osmnx

Data is requested by bounding box in [WGS84](https://en.wikipedia.org/wiki/World_Geodetic_System) coordinates.

You can find output Geometry in [Dropbox](https://www.dropbox.com/scl/fo/hqxrx8ns08oa7bay9oq2z/h?rlkey=8mtvopbd5w4tqb5bbimkloaj4&dl=0)

1. Environment set-up
   
   Before running notebooks from this repository make sure to install all dependencies by running the following commands:
    - python -m venv env  
    - env\Scripts\activate
    - pip install -r requirements.txt

2. The Federal Emergency Management Agency (FEMA) Dataset
   
   You can find more information about US Structures here: https://gis-fema.hub.arcgis.com/pages/usa-structures The dataset contains information about:
   - building types
   - building height
   - CENSUS number

3. [Open Street Maps (OSM)](https://www.openstreetmap.org/) and [osmnx](https://osmnx.readthedocs.io/en/stable/ )
   
   For documentation visit https://osmnx.readthedocs.io/en/stable/ 
   - includes building footprints
   - highways and roads geometry
   - points of interest

4. [USGS](https://www.usgs.gov/)
   
   REST Servises: https://tnmaccess.nationalmap.gov/api/v1/docs
   - LiDAR point clouds
   - Topography
   - Forests