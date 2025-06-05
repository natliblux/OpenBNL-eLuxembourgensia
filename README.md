# OpenBNL-eluxembourgensia
This project makes use of Open Data from the BnL and Wikidata to provide a list of newspapers that were published during the lifetime of a Luxembourgish person.
## Introduction
This project uses Jupyter Notebooks to encapsulate all information regarding the project.
The notebook requests the name of a person from the user.  It then queries Wikidata via it's [API interface](https://commons.wikimedia.org/w/api.php?action=help&modules=main) to retrieve information about that person. If more than one response is provided, the user will be prompted to select the desired Wikidata entry.  From that, the birth and death date of the person are used to select a list of newspapers published during that time period.
## Requirements
* Python 3.12
* [requests](https://pypi.org/project/requests/): HTTP library to run HTTP requests
* [pandas](https://pandas.pydata.org/): format the output into tabular layout
* [yarl](https://pypi.org/project/yarl/): format the output URL into a clickable URL link
## Usage
The notebook can be run online using [Binder/JupyterLab](https://mybinder.org/v2/gh/natliblux/OpenBnL-eluxembourgensia/c677069a62cb2b06be9c6d07782b3940fb3c349a?urlpath=lab%2Ftree%2Fsrc%2FQuerying%20eLuxembourgensia.ipynb).
## Result
Below is a sample of the results produced by this project.

![Sample results](Sample%20results.jpg)
