# OpenBNL-eLuxembourgensia
This project makes use of Open Data from the BnL and Wikidata to provide a list of newspapers that were published during the lifetime of a Luxembourgish person.
## Introduction
This project uses Jupyter Notebooks to encapsulate all information regarding the project.
The notebook requests the name of a person from the user.  It then queries Wikidata via it's [API interface](https://commons.wikimedia.org/w/api.php?action=help&modules=main) to retrieve information about that person. If more than one response is provided, the user will be prompted to select the desired Wikidata entry.  From that, the birth and death date of the person are used to select a list of newspapers published during that time period.
## Requirements
* Developed using Python 3.12
* [requests](https://pypi.org/project/requests/): HTTP library to run HTTP requests
* [pandas](https://pandas.pydata.org/): format the output into tabular layout
* [yarl](https://pypi.org/project/yarl/): format the output URL into a clickable URL link
## Usage
Once completed, the notebook can be run online using [Binder/JupyterLab](https://mybinder.org).
## Result
Below is a sample of the results produced by this project.
