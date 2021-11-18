# cci-ocean-colour

TThe Ocean Colour Climate Change Initiative (CCI) is a European Space Agency (ESA) funded project that focuses on the Ocean Colour Essential Climate Variables (ECV). This multi-sensor time-series product includes water-leaving radiance in the visible domain, derived chlorophyll and inherent optical properties and utilises data archives from Copernicus, ESA, NASA and NOAA. Further detail about accessing the dataset are available from: https://climate.esa.int/en/projects/ocean-colour/data/

This repository showcases some ESA CCI ocean colour data extraction and plotting using examples using Jupyter Notebooks. These examples were developed using information from the [Product User Guide](https://docs.pml.space/share/s/dPL4zFuaT_eFa-mTLU9nQA), with the support of Tom Jackson (PML).

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
