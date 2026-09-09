# Does Ford Cause More Fatal Crashes?

## Team

CIS 3920 Group 6, Spring 2026

Shazrim Farin, Swikriti KC, Ethan Ma, Geovanni Ramos

## Research Question

Does Ford vehicle involvement significantly increase the probability of a fatal crash after controlling for crash conditions and driver characteristics?

## Data

The project used NYC Motor Vehicle Collision data sourced from NYPD crash records.

The raw dataset contained 89,102 observations across 27 columns. After cleaning and preparing the model variables, the final analysis dataset contained 70,272 observations.

Only 39 of the 70,272 crashes were fatal, giving a fatal crash rate of about 0.055 percent. Ford vehicles appeared in about 10.1 percent of the analyzed crashes.

## Variables

The main outcome was `IS_FATAL`.

The key variable of interest was `IS_FORD`.

The adjusted logistic regression also included:

* `IS_RECKLESS`
* `IS_LICENSED`
* `IS_LARGE_VEHICLE`
* `IS_OLD`
* `IS_MALE`
* `IS_DAYLIGHT`
* `IS_WEEKEND`
* `IS_RUSH_HOUR`

## Model

The team used binary logistic regression to study fatal crash outcomes. The adjusted model was statistically significant overall with an LLR p value of 0.003674.

The complete regression output is preserved in [`results/model_output.txt`](results/model_output.txt).

## Main Findings

In the adjusted model, Ford involvement had a coefficient of 0.7343 with a p value of 0.070, so it was not statistically significant at the conventional 0.05 level.

Large vehicle involvement had a positive coefficient of 0.6626 with a p value of 0.049.

Rush hour had a negative coefficient of 1.0723 with a p value of 0.038.

The results suggested that vehicle type and traffic conditions were more informative for fatal crash risk than vehicle brand alone.

## Limitations

Important factors such as weather, road type, speed limits, traffic density, and actual vehicle speed were not directly available in the analysis.

## Attribution

This was a four person academic team project. The materials in this repository document the project and should not be interpreted as work completed by one person alone.
