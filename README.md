# cci-ocean-colour
ESA CCI ocean colour data extraction and plotting using examples within. 

## Anaconda environment installation
* Install in steps
    + ```conda create -n ocolour python=3.8```
    + ```conda activate ocolour```
    + ```conda config --add channels conda-forge```
    + ```conda install xarray dask netCDF4 bottleneck```
    + ```conda install tqdm matplotlib```
    + ```conda install nb_conda ipykernel```
    + ```pip install ipywidgets```
OR 
* Install from environment file (edit the path):
```conda env create -f ocolour.yml python=3.8```
  
## To run
* Activate environment if not already active (see prompt): ```conda activate ocolour```
* Run: ```anaconda_navigator``` or ```jupyter_notebook``` to launch jupyter notebooks 

Note: If the ocolour environment does not appear as a listed kernel then run ```python -m ipykernel install --user --name ocolour --display-name "Python 3-8 (ocolour)"```
