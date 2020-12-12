# Visualize spatial point-based Data and its density with python basemap

### Description

In earth science, coordinate-based data, or we commonly called it spatial data is one of the crucial data when doing research. Since it has important information about a particular phenomenon that transpired within a certain region of the earth, we ought to analyze and visualize the data properly. In Meteorology, we use spatial data to visualize some atmospheric parameters such as temperature, humidity, precipitation, cloud cover, etc. The advantage of having spatial data is you can figure it on a world map since the parameter values are available for every part of the region. 

In this project, I use different spatial data. My data only contains two attributes of location which are Longitude and Latitude (in degree), and not all the coordinates have the value or parameter. Each attribute represents the centroid of *MCC (Mesoscale Convective Complex)*. MCC is is a cloud organization that has an area of more than 50,000 km2, eccentricity of more than 0.7, and a life span of more than 6 hours (Maddox, 1980).

For the more details about this project. Please kindly check my Medium here: [How to visualize spatial point-based data and its density with python Basemap?](https://medium.com/@tiofaizintio/how-to-visualize-spatial-point-based-data-and-its-density-with-python-basemap-bfe6d9da76df)

### Required Libraries
The followings must be successfully installed before starting the project:
1. Matplotlib
2. Numpy
3. Scipy
4. Basemap
5. Xlrd (optional, depends on your data format).

### Basemap Installation
Basemap is a great tool for creating maps using python in a simple way. It's a matplotlib extension, so it has got all its features to create data visualizations, and adds the geographical projections and some datasets to be able to plot coast lines, countries, and so on directly from the library.

In some my colleagues' python environment, installing basemap is a bit tricky. Basemap could possibly impact your existing libraries in your environment and turn your libraries under error (Some errors might be hard to identify). Consequently, I fully recommend you creating a new environment, install/upgrade basic libraries, and install Basemap (Don't install basemap on your base environement).

To install Basemap package with conda run:
<br>`conda install -c anaconda basemap`

or, download the package first: [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#basemap), and:
<br>`pip install basemap-1.0.8-cp34-none-win_amd64.whl`

### Licence
This is public domain work, dedicated using [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Feel free to do whatever you want with it.
