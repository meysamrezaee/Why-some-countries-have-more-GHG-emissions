Project name: why some countries have more GHG emissions

Goal: Collect multiple variables from different dataset, merge them into one dataset, and find out which variables affects green house gas (GHG) emissions and which don't.

Skills required:
  - Data collection
  - Python programming
  - Understanding Numpy, Pandas, Seaborn libraries
  - Understanding statistical concepts such as correlation, scatter plots, and histograms

Results:
  - Variables that have a high correlation with CO2 emission:
    - Population: 0.85
    - Surface area: 0.51
    - GDP: 0.94
    - Fossil fuel production: 0.87
    - Fossil fuel consumption: 0.997
  - Variables that are not correlated with CO2 emissions:
    - Urban population percentage: -0.13
    - GDP per capita: -0.13
    - Exchange rate: -0.03
    - Life expectancy: -0.12
    - Fertility rate: -0.05
    - Infant mortality: 0.09

Data used from:
https://data.un.org/
  SYB62_1_201907_Population, Surface Area and Density.csv
  SYB61_253_Population Growth Rates in Urban areas and Capital cities.csv
  SYB62_230_201904_GDP and GDP Per Capita.csv
  SYB62_130_201907_Exchange Rates.csv
  SYB62_246_201907_Population Growth, Fertility and Mortality Indicators.csv
https://ourworldindata.org/fossil-fuels
  fossil-fuel-production-over-the-long-term.csv
  coal-consumption-by-country-terawatt-hours-twh.csv
  oil-consumption-by-country.csv
  gas-consumption-by-country.csv
https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions
  annual-co2-emissions-per-country.csv
https://www.worldometers.info/geography/alphabetical-list-of-countries/
  CountryNames.csv

