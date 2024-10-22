# Textured Terrain Dataset

The textured terrain dataset consists of 42,379 RGBA imagess, each with a resolution of 256x256. The RGB channels of the images hold the earth's surface data and the A channel has the corresponding heightmap. 

All data was obtained from Google Earth Engine. The heightmap images are from [SRTM](https://developers.google.com/earth-engine/datasets/catalog/USGS_SRTMGL1_003) Courtesy NASA/JPL-Caltech, while the surface images are from [Landsat 8 Level 2, Collection 2, Tier 1](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C02_T1_L2), courtesy of the U.S. Geological Survey.
Both datasets have a precision of 1 arc second (~30 meter\pixel).

The RGBA_train.txt, RGBA_validation.txt, and RGBA_test.txt files split the data randomly into three subsets: 80% for training, 10% for validation, and 10% for testing
