# Analysing Movie Ratings on Fandango

## Project Overview
This project investigates whether Fandango manipulated movie ratings by rounding them up unfairly, as highlighted in Walt Hickey's analysis. The datasets used in this analysis include movie ratings before and after the controversy:

• 2015 Data (`fandango_score_comparison.csv`)

• 2016–2017 Data (`movie_ratings_16_17.csv`)

The goal is to determine if Fandango's rating system changed after the controversy and whether the reported issue was indeed fixed.

## Data Sources

**`fandango_score_comparison.csv`** (2015 movies):

• Contains movie ratings from Rotten Tomatoes, Metacritic, IMDb, and Fandango.

• Includes both raw and normalised ratings.

• Features vote counts and a computed Fandango rating difference.

**`movie_ratings_16_17.csv`** (2016–2017 movies):

• Similar structure with ratings from major review aggregators.

• Includes normalised (*`n_`*) and re-scaled (*`nr_`*) ratings.

## Analysis Approach

### 1. Data Inspection & Cleaning

• Load and explore the datasets.

• Standardise column names and formats for consistency.

### 2. Comparing Fandango Ratings (2015 vs 2016–2017)

• Check if Fandango's rating trends changed post-controversy.

• Analyse the differences between Fandango ratings and other review platforms.

### 3. Findings & Conclusion

• Assess whether Fandango made adjustments after the controversy.

• Determine if their claims of fixing the issue hold up based on the data.

## Results

• The analysis suggests that **Fandango's ratings in 2016–2017 were generally lower than in 2015**, indicating a potential adjustment.

• The differences between Fandango ratings and other platforms also appear to have decreased, supporting Fandango’s claim that the issue was addressed.

## Techniques Used

• **Python** (Pandas for data manipulation and analysis)

• **Jupyter Notebook** (for interactive analysis)

• **Matplotlib/Seaborn** (if visualisations were included)

## Conclusion

This project explores Fandango's rating trends over time and evaluates whether the company adjusted its rating system after being exposed. The analysis provides insights into potential biases in rating aggregation platforms and their impact on public perception.

