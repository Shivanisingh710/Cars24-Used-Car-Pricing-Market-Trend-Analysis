## Project Overview

This project focuses on scraping used car listing data from Cars24 across multiple Indian cities and performing data cleaning and preprocessing using Python and Pandas. The final cleaned dataset contains around 220 car records with important details related to pricing, fuel type, transmission, EMI, registration state, and manufacturing year.

## Objectives

* Scrape used car listing data from Cars24
* Clean and preprocess raw scraped data
* Handle missing values, inconsistent data and inconsistent formats
* Create analysis-ready structured dataset
* Prepare data for visualization and analytics

## Dataset Columns

* Cars (contains car name)
* Model
* Dist per km (Total dist covered till now)
* Fuel Type
* Transmission
* Registration Number
* EMI Per Month
* Sale City
* Manufacturing Year
* Registered State
* Actual Price in Lakhs
* Discounted Price in lakhs
* Other Charges

## Tools & Libraries Used

* Python
* Pandas
* Numpy
* Glob
* BeautifulSoup
* Requests
* Jupyter Notebook

## Data Cleaning Performed

* Removed null
* Standardized text formatting
* Converted price and EMI columns into numeric format
* Extracted manufacturing year from the car name
* Extracted reg_state from registration number information
* Added structured columns like discount%, Car Age and brand name for easier analysis

## Future Scope

* Power BI dashboard creation
* Used car price prediction
* City-wise and brand-wise trend analysis
* Depreciation and resale value insights
