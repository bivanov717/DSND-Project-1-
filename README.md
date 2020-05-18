# Hotel Booking Demand Analysis

## Project motivation
In this repo you'll find the analysis I did for the data scientist nanodegree using public data from Kaggle on hotel reservations. I was interested in finding out: 

1.	What is the lead time of bookings, does this differ if it is a family holiday and how is price related to lead time?
2.	What are the features that highly correlate to price (Average Daily Rate)?
3.	What are the most popular months for holidays? 

## File Description

For this project there are:
-	one data file - DSDN Project 1 Hotel Data.csv
-	one notebook available - DSDN Project 1.ipynb

## Requirements

- Pandas
- Numpy
- Matplotplit
- Seaborn
- Jupyter Notebook(only if running locally)

## Results

The analysis helped come to the following conclusions:
1. Lead time appears to be about 100 days for all holidays, with family holidays having slightly shorter lead time, compared to non-family. The price and lead time have a small negative correlation.
2. The main explanatory variables for price (Average Daily Rate) appear to be Reserved Room Type, Assigned Room Type and Market Segment.
3. The bookings are predominantly spread within the summer months, with a fall down in the winter.

A full blog post describing the results can be found here: https://medium.com/@b_ivanov/analyzing-hotel-demand-data-eeac278ea8c5

# Acknowledgements
I got the data from Kaggle: https://www.kaggle.com/jessemostipak/hotel-booking-demand
