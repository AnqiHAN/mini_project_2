# IPEN5810_Mini_Project_2 Global Trade Patterns
by HAN Anqi, LIU Bowen

# 1. Objectives
To classify topics embedded in employer reviews, drawn from a randomly sampled dataset. 

# 2. Requirements

There are some general library requirements for the project, and some are specific to individual methods. The general requirements are as follows:
* `dask`
* `numpy`
* `pandas`
* `geopandas`
* `matplotlib.pyplot`


The library requirements specific to some methods, which will be shown in the following **methodololgy** section.

**Note**: It is recommended to use Anaconda distribution of Python.

# 3. Description of dataset
Each trade flow within BACI is characterized by a combination of exporter-importer-product-year. We provide the value and the quantity.

BACI contains 6 variables:

`t` Year

`k` Product category (HS 6-digit code)

`i` Exporter (ISO 3-digit country code)

`j` Importer (ISO 3-digit country code)

`v` Value of the trade flow (in thousands current USD)

`q` Quantity (in metric tons)

In addition to the core BACI files, we provide two additional set of files:

`country_codes` Associates the ISO 3-digit country codes to country names

`product_codes` Associates the HS 6-digit product codes to product names
# 3. Descriptive Data Analysis
**1 Trading Partners**
**2 Trading Volume**
**3 Trading Product**
**4 Trading Distance** in example with distance to China

# 4. Trading Pattern
**1 Countries share similar Num of Trade Partners**
**2 Countries share similar Trade Volume**

# 5. Predicting Trading Flows
**1 Countries share similar Num of Trade Partners**
**2 Countries share similar Trade Volume**

