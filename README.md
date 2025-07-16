# Department of Health and Mental Hygiene Analysis

## Project Overview
We're assisting the Department of Health and Mental Hygiene within NYC to explore which areas need medicine most. We investigated the data to gain further insight of boroughs in NYC and their frequency of influenza/pneumonia visits.

# Which borough needs more influenza/pneumonia medication?

## Data Cleaning

- Took a random sample of 1000 encounters in the hospital between the years of 2020-2022.
- Removed time from "date" column for more utility.
- Changed "date" column to DateTime for our visualizations.
- Renamed "mod_zcta" to "zip_code" for legibility.
- Created new column for "borough" by filtering and using a for loop through "zip_code" column.

# Medical Analysis

1. Brooklyn has the **HIGHEST** number of pneumonia/infleunza visits and admissions.

2. Brooklyn has the **HIGHEST** percentage of admissions vs visits.

3. Brooklyn's pneumonia/influenza visits has had the **highest rate** of increase between all boroughs from the years 2020-2022.

4. Of the top 5 zip codes with highest pneumonia/influenza vists, Brooklyn accounts for **60%** and has the **highest plurality** in the top 10 visits with 4 instances.


## As shown in our analysis, Brooklyn is most in need of influenza/pneumonia medicine