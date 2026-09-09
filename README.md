# NYC Motor Vehicle Collision Fatality Analysis

Academic team project completed for CIS 3920 Data Mining for Business Analytics at Baruch College in Spring 2026.

## Project Overview

This project examined whether Ford vehicle involvement was independently associated with fatal crash outcomes after accounting for driver, vehicle, and time related factors in NYC motor vehicle collision data.

I worked as part of a four person team with Shazrim Farin, Ethan Ma, and Geovanni Ramos.

## Actual Project Materials

* [`team_project_details.md`](team_project_details.md) documents the final research question, dataset, model, findings, and team attribution.
* [`results/model_output.txt`](results/model_output.txt) contains the actual statsmodels logistic regression output from the project.

## Dataset

The analysis started with 89,102 collision records across 27 columns. After cleaning and preparing the modeling data, the final dataset contained 70,272 observations.

Fatal crashes were very rare in the final dataset, with 39 fatal crashes, or about 0.055 percent of observations.

## Methods

Python, pandas, logistic regression, data cleaning, feature engineering, model evaluation, and statistical interpretation.

## Key Findings

Ford involvement was not statistically significant at the 0.05 level after controlling for the other variables in the model.

Large vehicle involvement was positively associated with fatal crash risk, while rush hour crashes were negatively associated with fatal outcomes in the fitted model.

## Project Context

This was a four person academic team project. The repository documents the analysis without presenting the full team project as individual work.
