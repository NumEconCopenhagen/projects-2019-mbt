# Welcome to MBT's course repository

This is the repository for the group *MBT*. 

The repository contains the following folders:

* [/dataproject](/dataproject): The data analysis project.
* [/modelproject](/modelproject): The model analysis project.
* [/examproject](/examproject): The exam project.

## Data analysis project
### Tourism in Denmark

The data project is an insight into the extent of tourism in Denmark. Statistics Denmark has records of have many foreigners, who spend the night in one of Denmark’s many hotels, camping sites etc. The observations are monthly data from 2014-2018, broken down by the nationality of the tourists and which region in Denmark they staying overnight. First the evolution of the level of tourism is examined and then the seasonal effects are extracted. Finally, the characteristics of the visiting tourists is closely studied. The interesting questions are who is visiting Denmark, and where do they live?

For the analysis and data handling, a bunch of different packages and a shape-file for the administrational borders in Denmark is used. Everything is documented in the Jupyter Notebook. The shapefile (.shp) is also uploaded in the repository in the folder "Geofiles".

The **results** of the project can be seen from running [/dataproject](/dataproject).

**Dependencies:** Following packages is required to run the code:

- conda install -c conda-forge geopandas (since it is conda, it might take some time)
- pip install -U statsmodels
- pip install pydst

Other packages used in the lectures is expected to be installed by the reader.


## Model analysis project
### The Koopman model - Robinson Crusoe economy
##### What is the Robinson Crusoe economy?

Imaging the classic everyday first world problem. You are on your way to a tropical paradise for the holidays, but on the way your plane crashes and leaves you stranded on a deserted island. As a human being, you have to eat in order to survive and the island only has two kinds of food supplies. You can either use your time on fishing or pick bananas. Each activity consumes time of the day, which you would rather spend on relaxation/leisure (since this technically is your holiday). As a rational utility optimizing individual with understanding of economic efficient decision making, you now have to decide how to allocate your time in order to achieve the maximum amount of utility (remeber it is you holiday, so you should get the most out of it).

The project will solve the standard Robinson Crusoe economy by finding the pareto efficient allocation between two goods in order to optimize the utility of the agent. After the model is optimized, the model will be extened by looking at comparative advantages. Instead of just including an extra agent in the model, a completely new model is presented in order to show how the comparative advantage work in general. 

The **results** of the project can be seen from running [/modelproject](/modelproject).

**Dependencies:** All packages used for the project should be part of the standard anaconda installation.

Happy reading!
