### This repository will hold slides, notebooks, and data for NSS Data Analytics and Data Science students to learn to work with geospatial data. 

### Getting Started With the Geospatial Environment
To run the notebook for this project, you will need some additional python packages. 
You can install these using conda. 
We have provided an `environment.yaml` file with the packages to be used for the project.
This `environment.yaml` file will create a new environment for you called `geospatial`.

Open your terminal, and `cd` into this project. 
From there run: 
```bash
conda env create -f environment.yaml
```

Once this has been created for you, you can then use it within Anaconda Navigator (like your base environment), or continue using it from the command line.
For example, to open a new session with jupyter, you could then run: 
```
conda activate geospatial
jupyter-notebook
```

#### Introduction slide deck and notebooks covers 
 - importance of location to some kinds of analysis
 - `geopandas` GeoDataFrames
 - types of geometry
 - intro to coordinate reference systems
 - spatial joins
 - adding context with `folium` maps
    - constructing maps
    - markers
    - marker clusters
    - popups