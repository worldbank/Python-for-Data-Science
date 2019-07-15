# Creating a virtual environment for this week's class

**Requirements for this week:** We'll use `requests` (for APIs), and `OSMNX` and `Geopandas` (for geospatial). We'll also call on pandas, numpy, Seaborn, and mplleaflet. Create an environment with these libraries. Any difficulties, create an environment with just geopandas and requests.

**Suggested installation commands (adjust if necessary):**

* conda create -n APIs_geospatial Python=3.7
* conda activate APIs_geospatial
* conda install -c conda-forge osmnx -y
* conda install seaborn -y
* pip install mplleaflet
* conda install ipykernel -y
* python -m ipykernel install --user --name APIs_geospatial --display-name APIs_geospatial 

**Recap and resources:**
* Virtual environments allow you to create several different Python installations, each with a different set of libraries.
* You can install libraries with the `conda install` or `pip install` commands. Conda is a more sophisticated package manager than pip; note that `conda install geopandas` would install the geopandas library and all the other libraries that it depends on (Pandas, Numpy, requests etc).
* Be aware that conda has several additional channels, beyond its default one, such as conda-forge. The -y suffix asks Conda to go ahead with installation without prompting you for confirmation.
* If you have difficulties (it happens), consult the conda [cheat-sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf), our full [readme](https://github.com/worldbank/Python-for-Data-Science/blob/master/anaconda_virtual_environments.md), or create a new virtual environment and just try again.

