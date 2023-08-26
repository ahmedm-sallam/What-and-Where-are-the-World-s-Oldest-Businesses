# What-and-Where-are-the-World-s-Oldest-Businesses
![Staffelter Hof Winery](https://upload.wikimedia.org/wikipedia/commons/2/22/MKn_Staffelter_Hof.jpg)

Welcome to the repository for "The Oldest Businesses in the World" project! In this project, we explore the fascinating history of some of the world's oldest businesses that have stood the test of time, operating through centuries of change and upheaval. From wineries to restaurants, this project dives into the history of businesses that have persisted for hundreds of years.

## Project Overview

The aim of this project is to understand what characteristics enable businesses to survive and thrive over incredibly long periods of time. To accomplish this, we've collected data on the oldest businesses in almost every country, spanning various industries and continents. By analyzing this data, we can uncover patterns, insights, and trends that contribute to the longevity of these establishments.

## Datasets
We have compiled datasets containing information about the oldest businesses, countries, and business categories. Here's a breakdown of the datasets:
### 1. businesses.csv
This dataset contains information about the oldest businesses, including their names, founding years, category codes, and country codes.
* `business`: Name of the business.
* `year_founded`: Year the business was founded.
* `category_code`: Code for the category of the business.
* `country_code`: ISO 3166-1 3-letter country code.
### 2. countries.csv
This dataset provides details about countries, including their names and continents.

* `country_code`: ISO 3166-1 3-letter country code.
* `country`: Name of the country.
* `continent`: Name of the continent that the country exists in.

### 3. categories.csv
This dataset describes the business categories corresponding to the category codes.

* `category_code`: Code for the category of the business.
* `category`: Description of the business category.
### 4. new_businesses.csv
In this dataset, we've added information about the oldest businesses in countries where the data was missing.

* `business`: Name of the business.
* `year_founded`: Year the business was founded.
* `category_code`: Code for the category of the business.
* `country_code`: ISO 3166-1 3-letter country code.
  
## Project Code
To perform analysis and generate insights from the datasets, we've provided Python code snippets using the pandas library. Here's a brief overview of the code sections:
1. **Exploring Oldest Businesses**: We start by loading the data and sorting the oldest businesses based on their founding years.
2. **Oldest Businesses in North America**: We explore the oldest businesses in North America by merging data from different datasets and filtering by continent.
3. **Oldest Business on Each Continent**: We identify the oldest businesses on each continent by grouping and merging data.
4. **Unknown Oldest Businesses**: We find countries without known oldest businesses by comparing datasets.
5. **Adding New Oldest Businesses**: We fill missing data using a dataset containing new oldest businesses.
6. **Oldest Industries**: We explore industries with the most oldest businesses.
7. **Restaurant Representation**: We focus on the oldest restaurants founded before 1800.
8. **Categories and Continents**: We identify the oldest businesses in each category for each continent.

## Conclusion
This project sheds light on the remarkable resilience and longevity of businesses across the world. By analyzing historical data, we've gained insights into the factors that contribute to their enduring success. Whether it's a winery, a restaurant, or a financial institution, these businesses have navigated through centuries, leaving a lasting impact on their respective industries.
