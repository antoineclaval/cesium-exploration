# Testing out cesiumjs lib to display interactive 3D globe in the browser

## Docker for the win

- https://github.com/geo-data/cesium-terrain-server
- https://github.com/tum-gis/cesium-terrain-builder-docker

GDAL virtual dataset instructions : https://github.com/tum-gis/cesium-terrain-builder-docker#create-a-gdal-virtual-dataset-optional

## Running it 
mkdir -p /data/docker/tilesets
docker run -p 8080:8000 -v /data/docker/tilesets/terrain:/data/tilesets/terrain     geodata/cesium-terrain-server
