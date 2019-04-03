# Dataproject

The data project is an insight into the extent of tourism in Denmark. Statistics Denmark has records of have many foreigners, who spend the night in one of Denmark’s many hotels, camping sites etc. The observations are monthly data from 2014-2018, broken down by the nationality of the tourists and which region in Denmark they stay. First the evolution of the level of tourism is examined and then the seasonal effects are extracted. Finally, the characteristics of the visiting tourists is closely studied. The interesting questions are who is visiting Denmark, and where do they live?

For the analysis and data handling, a bunch of different packages and a shape-file for the administrational borders in Denmark is used. Everything is documented in the Jupyter Notebook. The shapefile (.shp) is also uploaded in the repository in the folder "Geofiles".

Following packages is required to run the code:

- conda install -c conda-forge geopandas (since it is conda, it might take some time)
- pip install -U statsmodels
- pip install pydst

Other packages used in the lectures is expected to be installed by the reader.

Happy reading!

/MBT
