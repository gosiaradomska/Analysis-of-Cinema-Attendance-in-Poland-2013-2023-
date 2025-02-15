# Analysis-of-Cinema-Attendance-in-Poland-2013-2023

## Project Description

This project was carried out as part of the “Data Source Integration Modeling” course in the 5th semester of the Engineering and Data Analysis program. The work was conducted in two-person teams and is written in Polish, as it was a university project.

The goal was to choose a topic for analysis, find appropriate datasets, select relevant variables, build an econometric model, and verify its accuracy.

## Data Source

The dataset was obtained from the [Local Data Bank](https://bdl.stat.gov.pl) and includes 17 features describing cinema attendance in Poland from 2013 to 2023.

## Analyzed Variables

Dependent Variable (Y): Number of cinema viewers in Poland.

Independent Variables (X):

* Number of cinemas, screening rooms, and seats,

* Number of screenings,

* Population in different age groups,

* Salaries, television subscriptions, cultural expenses,

* Number of mass entertainment events, public transport usage, ticket prices.

## Methods of Analysis

* Descriptive statistics and visualizations (mean, standard deviation, histograms, bar charts).

* Variable selection for the model:

  * Correlation matrix,

  * Hellwig’s method,

  * Linear regression analysis.

* Model parameter estimation using the least squares method.

* Model verification:

  * Fit evaluation (R², F-statistic, p-values),

  * Normality tests for residuals,

  * Autocorrelation tests (Durbin-Watson, Breusch-Godfrey),

  * Heteroscedasticity tests (Breusch-Pagan, White’s test),

  * Series test to check randomness of residuals,

  * Symmetry test to verify distribution properties.

## Results and Conclusions

The model explains 97.03% of the variance in cinema attendance.

Key influencing variables:

* X5: Population of pre-working age in urban areas,

* X12: Number of mass entertainment events,

* X13: Cultural spending per capita.

The model meets the assumptions of classical linear regression.

## Technologies and Tools

Programming Languages: Python / R / Excel (Data Analysis Tool)
