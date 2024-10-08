# assignment
NCEI Climate Data Analysis Project
Project Description
This project leverages climate data from the National Centers for Environmental Information (NCEI). The dataset used in this analysis is a subset of the Daily Global Historical Climatology Network (GHCN-Daily), which consists of daily climate records from various land surface stations across the globe.

The objective of this project is to analyze and visualize temperature trends for a specific region (Ann Arbor, Michigan, United States) and identify record high and low temperatures over the period of 2005-2014. The project includes:

Visualizing record highs and lows by day of the year.
Highlighting any new record-breaking temperatures observed in 2015.
Visualizing the geographical distribution of weather stations on a map.
Providing a summary of temperature trends for the region.
Dataset Information
The dataset used for this project consists of the following variables:

id: Station identification code
date: Date in YYYY-MM-DD format (e.g., 2012-01-24 = January 24, 2012)
element: Indicator of element type
TMAX: Maximum temperature (tenths of degrees C)
TMIN: Minimum temperature (tenths of degrees C)
value: Data value for the element (tenths of degrees C)
Data Processing and Visualization
Data Cleaning: Handling missing values, filtering relevant data (2005-2014), and removing leap day data points (February 29th).
Temperature Trends Analysis: Calculating record highs and lows for each day of the year over the period 2005-2014.
New Records Detection: Comparing the 2015 data to identify if any new record highs or lows were set.
Visualization: Creating line charts with shaded areas between the record high and low temperatures and scatter plots for 2015 records.
