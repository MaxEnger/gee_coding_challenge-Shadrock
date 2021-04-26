# Developing a Script to visualize 20-Year Median NDVI Trends in Argentina and Tierra Del Fuego
The script developed in this analysis generates an animated GIF representing 20-year median NDVI for serial 16-day MODIS composites spanning January 1st through December 31st. The tutorial uses [MODIS](https://modis.gsfc.nasa.gov/), a moderate resolution satellite, and [NDVI](https://en.wikipedia.org/wiki/Normalized_difference_vegetation_index), which is a common reflectance-based vegetation index. The [Earth Engine Data Catalog](https://developers.google.com/earth-engine/datasets/) provides NDVI as a precalculated [dataset](https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MOD13A2) for convenience. The script was developed by following this tutorial: [MODIS NDVI Times Series Animation tutorial on the GEE community web site](https://developers.google.com/earth-engine/tutorials/community/modis-ndvi-time-series-animation)

# 20-Year Median NDVI Trends in Argentina
In this tutorial, you'll learn how to generate an animated GIF representing 20-year median NDVI for serial 16-day MODIS composites spanning January 1st through December 31st. The tutorial uses [MODIS](https://modis.gsfc.nasa.gov/), a moderate resolution satellite, and [NDVI](https://en.wikipedia.org/wiki/Normalized_difference_vegetation_index), which is a common reflectance-based vegetation index. The [Earth Engine Data Catalog](https://developers.google.com/earth-engine/datasets/) provides NDVI as a precalculated [dataset](https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MOD13A2) for convenience.
> ![NDVI Animation of Argentina](images/argentina_NDVI.gif)

# Trends at the End of the Earth: Tierra Del Fuego
Once you've completed the NDVI tutorial, write a script for GEE that will create the same output (an animated .gif) for a specific country. Choose any country you like. Once completed, copy the code from your GEE file into a `.js` file and place it in a new Github repo. Place your animated `.gif` in the same repo and embed it in your `README`. You will submit a link to your repo containing the code, your animated gif, and a brief write-up in your `README` about the country you selected and any observations you have. Your output should look something like this (I chose Argentina):
> ![NDVI Animation of Tierra Del Fuego](images/TierraDelFuego_NDVI.gif)
