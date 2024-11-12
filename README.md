# potato_crop_detection

## Detection of potato crops in advanced vegetative stage using Sentinel 2 with remote sensing in the Peruvian Andes

This is the repository of files used to build the database for this study.

All satellite images were obtained using the Sentinel-2 API in Python.

The file "polygons.geojson" contains georeferenced agricultural area polygons that were constructed as the initial database. All polygons are represented in EPSG:3035 format and include the "category" column to indicate the type of area they represent.

The file "pixels.csv" contains the pixel database used to train the models. It includes Sentinel-2 spectral bands and vegetation indices derived from them. The "label" column refers to class "1" for pixels in developed potato crop areas and class "0" for all other areas that make up the negative class.

All files were updated as of 11/11/2024.
