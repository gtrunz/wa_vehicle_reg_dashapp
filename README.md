# Washington Vehicle Registration Dashboard - Local

This repository contains the code used to process the data and launch the Washington Vehicle Registration Dashboard on a local machine from Jupyter. 

# Viewing the Dashboard Online

The dash_code.ipynb file was modified slightly to publish the app online. The app is available at: https://gtrunz.pythonanywhere.com/ . It was developed primarily for laptop and desktop use and is not optimized for smartphones or other devices.

# Code/Packages Used

 - `prep_code.ipynb` prepares all of the data using a combination of PySpark, SQL, and Pandas.
   - python 3.8.15
   - pyspark 3.3.1
   - pandas 1.5.2
   - numpy 1.24.0
   - geopandas 0.12.2
   - geojson-rewind 1.0.0
   
 - `dash_code.ipynb` contains the code to launch the app locally.
   - python 3.9.18
   - pandas 2.0.3
   - geopandas 0.12.2
   - numpy 1.26.0
   - dash 2.7.0
   - plotly 5.10.0
   - geojson-rewind 1.0.0
   - statsmodels 0.14.0

# Data Sources/Notes
- This dashboard has no affiliation with the State of Washington.
- Vehicle registration data is from the State of Washington's Open Data Portal: https://data.wa.gov/Transportation/Vehicle-Registration-Transactions-by-Department-of/brw6-jymh
- Geographic data is from the Washington Geospatial Open Data Portal: https://geo.wa.gov/datasets/wadnr::wa-county-boundaries/explore
- County population and median income data are for 2020 and from the U.S. Census Bureau: https://data.census.gov/table/
