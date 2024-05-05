

# IPEN5810_Mini_Project_2 Global Trade Patterns
by HAN Anqi, LIU Bowen

# 1. Objectives
To classify topics embedded in employer reviews, drawn from a randomly sampled dataset. 

# 2. Requirements

There are some general library requirements for the project, and some are specific to individual methods. The general requirements are as follows:
* `dask`
* `numpy`
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
![Top 10 Countries with the Most Trading Partners](%22E:%5CHKUST%28GZ%29%5CT2%EF%BC%8C23-24%5CIPEN%20Data%20Science%5Cmini%20project%202%5CPlotting%5CTop%2010%20Countries%20with%20the%20Most%20Trading%20Partners.png%22)

![ottom 10 Countries with the Most Trading Partners](%22C:%5CUsers%5Chuawei%5CPictures%5CScreenshots%5CBottom%2010%20Countries%20with%20the%20Most%20Trading%20Partners.png%22)

# 4. Key Findings

### Target 1: Review Summary

### Target 2: Positive Review

### Target 3: Negative Review
