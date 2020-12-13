# CQI-coffee-tableau
A tool to help identify which coffee origin has the best score from the coffee 

## Data
This coffee review dataset is obtained from https://github.com/jldbc/coffee-quality-database.
It contains 1312 Arabica coffee reviews from the Coffee Quality Institute.

## Cleaned Data
The dataset is cleaned using Python in Jupyter Notebook. 
* Empty data is removed 
* Altitude data in ft is removed. All altitude data are in meters.

##  Exploratory Data Analysis (EDA)
* Correlations between Acidity, Sweetness, Total Cup Points and Mean Altitude
  *Acidity is more correlated with higher Total Cup Points, compared to sweetness.
  *Altitude is not correlated to acidity or sweetness of the coffee.
* Scatter plot with regression line of Acidity versus Total Cup Points
  *Positive correlation: Higher Total Cup Points tend to have higher Acidity

## Data Visualisation
Dataset is visualised in Tableau. Take a look [here](https://public.tableau.com/profile/celine4997#!/vizhome/CapstoneCoffee_Tableaudashbd/Dashboard1?publish=yes).
* Which country produces coffee with the best Total Cup Score?
* Which processing method would you prefer?
