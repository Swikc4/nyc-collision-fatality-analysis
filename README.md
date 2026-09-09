# NYC Motor Vehicle Collision Fatality Analysis

Academic team project completed for CIS 3920 Data Mining for Business Analytics at Baruch College in Spring 2026.

## Project Overview

This project examined whether Ford vehicle involvement was independently associated with fatal crash outcomes after accounting for driver, vehicle, and time related factors in NYC motor vehicle collision data.

I worked as part of a four person team to clean the data, engineer analysis features, build and evaluate a logistic regression model, and communicate the results.

## Dataset

The analysis started with 89,102 collision records across 27 columns. After cleaning and preparing the modeling data, the final dataset contained 70,272 observations with no missing values across the model variables.

Fatal crashes were very rare in the final dataset, with 39 fatal crashes, or about 0.055 percent of observations.

## Tools and Methods

* Python
* pandas
* scikit learn
* Logistic regression
* Data cleaning
* Feature engineering
* Model evaluation
* Statistical interpretation

## Features Examined

The model included variables related to vehicle make, vehicle size, reckless driving, licensing status, driver sex, daylight conditions, weekends, and rush hour periods.

## Key Findings

Ford involvement was not statistically significant at the 0.05 level after controlling for the other variables in the model.

Large vehicle involvement was positively associated with fatal crash risk, while rush hour crashes were negatively associated with fatal outcomes in the fitted model.

The results suggested that vehicle type and crash conditions were more informative than brand alone.

## Limitations

The analysis did not directly include several potentially important factors such as weather conditions, road type, speed limits, traffic density, and actual driving speed.

## Project Context

This was a team academic project. This repository is intended to document the analysis and the skills I applied rather than present the work as an individual project.