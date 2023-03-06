# arcgis_api_python_testing
Code to isolate and test issues with the ArcGIS API for Python

## raster_ops.ipynb
Adding a hosted Imagery Layer from AGOL to a WebMap in a Jupyter Notebook using the ArcGIS API for Python fails silently.
The WebMap widget in the Notebook doesn't show anything, and the Map Viewer in AGOL shows the following error message for the raster layer: "An error occurred loading this layer"

Python API Version 2.1.0.2

## webmap_text_property.ipynb
Workaround for issue in `raster_ops.ipynb`.

  * Get, set, and update the "text" item property of the WebMap to set the layerType
to "ArcGISTiledImageServiceLayer"

Python API Version 2.1.0.2
