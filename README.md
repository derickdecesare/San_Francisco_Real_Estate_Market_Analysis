# San_Francisco_Real_Estate_Market_Analysis
This is an interactive visualization of the San Francisco housing market that analyzes a multitude of variables.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas] (https://github.com/pandas-dev/pandas) - For data manipulation and analysis.

* [hvplot] (https://github.com/holoviz/hvplot) - For high-level plotting.

* [pathlib] (https://github.com/budlight/pathlib) - For importing cvs files using standarized file path notation.
---

## Datasets

Datasets pulled from Resources folder which contains csv files.

## Usage

### General

Upon launching the financial_planning_tools.ipynb run each cell sequentially, ensuring to import the required libraries.

### Calculate and Plot the Housing Units per Year

This analysis visulizes the trend in housing units per year in San Francisco from 2010 - 2016.

![Housing Units Graph](Images/zoomed-housing-units-by-year.png)

### Calculate and Pot the Average Sale Prices per Square Foot and Gross rent

This analysis visulizes the average sale price per square foot and gross rent in San Francisco from 2011-2016.

![Rent and Price](Images/avg-sale-px-sq-foot-gross-rent.png)

### Compare Sale Prices by Neighborhood

This analysis lets you choose different neighborhoods from the dropdown selector so you can compare the differences.

![By Neighborhood](Images/pricing-info-by-neighborhood.png)

### Build an Interactive Neighborhood Map

This interactive map visualtizes both gross rent and sale price per square foot in different neighborhoods in San Francisco.

![GEO VIEW](Images/6-4-geoviews-plot.png)

