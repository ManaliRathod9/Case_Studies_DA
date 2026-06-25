# Airbnb Data Analysis

## About This Project

In this project, I worked with Airbnb listing data to understand how listings are priced, which room types are common, which neighborhoods have more listings, and how reviews changed over time.

The main goal was to clean the dataset, explore it step by step, and answer simple business questions using Python charts and summaries.

## Questions I Answered

1. What is the distribution of listing prices?
2. Which room types are listed the most?
3. Which neighborhood groups have the most listings?
4. How does price change based on room type?
5. How did the number of reviews change over time?

## What I Did

I started by loading the dataset and checking the columns, data types, missing values, and basic statistics.

After that, I cleaned the data by:

* Handling missing values
* Converting the `last review` column into date format
* Removing duplicate rows
* Dropping columns that were not useful for this analysis
* Converting `price` and `service fee` from dollar text into numeric values

Then I created charts to make the data easier to understand.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Main Findings

* Airbnb prices are spread across many different price ranges.
* Entire home/apartment and private room are the most common room types.
* Manhattan and Brooklyn have the highest number of listings.
* Room type helps compare how prices are different across listing categories.
* Review activity changes over time, which helps understand customer activity on Airbnb.

## Files in This Project

* `AirBnb_Analysis.ipynb` - Main notebook with code and charts
* `airbnb_data.csv` - Dataset used for analysis
* `README.md` - Project summary

## What I Learned

This project helped me practice the full data analysis flow, from reading a dataset to cleaning it, creating charts, and writing insights in a clear way. It also helped me understand how data can be used to answer real business questions.

## Author

Manali Rathod
