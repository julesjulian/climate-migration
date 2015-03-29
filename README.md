# Climate Migration Model
A simple model to estimate migration due to temperature increase based on data from the World Bank and a few ad-hoc parameters.

##Input
* Openly accessible data made available by the World Bank (http://data.worldbank.org/) on the following variables:
  * Temperature by country
  * Population by country
  * GDP per capita by country
  * Refugees by country of origin
  * Refugees by country of asylum
* Temperature increase in degrees C
  
##Output
* Climate refugees by country

##Run
Run as a regular ipython notebook with
```bash
ipython notebook climate-migration.ipynb
```
or run as slideshow with
```bash
ipython nbconvert climate-migration.ipynb --to slides --post serve
```

##Disclaimer
This is by no means a scientific study. You are welcome to fork the repo and turn it into one.
