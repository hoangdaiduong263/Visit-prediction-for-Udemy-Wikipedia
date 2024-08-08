# Visit-prediction-for-Udemy-Wikipedia
This repository contains the data and analysis related to predicting the number of visits to the Udemy Wikipedia page using the fbprophet library. The dataset includes historical visit data along with key holiday information which could impact visit patterns.

**1. Data Description**

The dataset udemy_wikipedia_visits.csv contains multiple observations and several variables, each providing crucial information about the visits to the Udemy Wikipedia page. Below is a detailed description of each variable:
- Date: The date of the observation.
- Udemy: The number of visits to the Udemy Wikipedia page on the given date.
- Easter: A binary indicator (0 or 1) indicating whether the date corresponds to the Easter holiday.
- Christmas: A binary indicator (0 or 1) indicating whether the date corresponds to the Christmas holiday.
- Black_Friday: A binary indicator (0 or 1) indicating whether the date corresponds to Black Friday.

**2. Objective**

The objective of this analysis is to predict the number of visits to the Udemy Wikipedia page using the fbprophet library. By incorporating holiday effects, we aim to improve the accuracy of our visit predictions.
