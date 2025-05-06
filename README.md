# OpenBNL-eLuxembourgensia
This project makes use of Open Data from the BnL and Wikidata to provide a list of newspapers that were published during the lifetime of a Luxembourgish person.
## Introduction
This project uses Jupyter Notebooks to encapsulate all information regarding the project.
The notebook requests the name of a person from the user.  It then queries Wikidata to retrieve information about that person. If more than one response is provided, the user will be prompted to select the desired Wikidata entry.  From that, the birth and death date of the person are used to select a list of newspapers published during that time period.
## Requirements
* Developed using Python 3.12
* [requests](https://pypi.org/project/requests/): HTTP library
* [ipywidgets](https://pypi.org/project/ipywidgets/): provides interactive HTML widgets for Jupyter notebooks 
* [iPython](https://ipython.org/): interactive computer in Jupyter Notebooks
* [pandas](https://pandas.pydata.org/): format output
## Usage
Once completed, the notebook can be run online using [Binder/JupyterLab](https://mybinder.org).
## Result
Once completed, an example of the results will be included here.
