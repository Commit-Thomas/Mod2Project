# Department of Health and Mental Hygiene Analysis

## Project Overview
We're assisting the Department of Health and Mental Hygiene within NYC to explore which areas need medicine most. We investigated the data to gain further insight of boroughs in NYC and their frequency of influenza/pneumonia visits.

# Which borough needs more influenza/pneumonia medication?

## Data Cleaning

- Took a random sample of 50,000 encounters in the hospital between the years of 2020-2022.
- Crossed referenced our sample with larger data set to check for similar ratios of zip codes. (zip code 10000 is least represented)
<img width="297" height="241" alt="Screenshot 2025-07-17 at 10 59 29 AM" src="https://github.com/user-attachments/assets/40853560-ca50-4d38-b23a-d0d41d73abd3" />
- Removed time from "date" column for more utility.
- Changed "date" column to DateTime for our visualizations.
- Renamed "mod_zcta" to "zip_code" for legibility.
- Created new column for "borough" by filtering and using a for loop through "zip_code" column.
<img width="205" height="131" alt="Screenshot 2025-07-17 at 10 59 37 AM" src="https://github.com/user-attachments/assets/0ac68e00-08e5-4750-bc49-e6a572fa71a1" />

# Medical Analysis

1. Brooklyn has the **HIGHEST** number of pneumonia/infleunza visits and admissions.

2. Brooklyn's pneumonia/influenza visits has had the **HIGHEST RATE** of increase between all boroughs from the years 2020-2022.


## As shown in our analysis, Brooklyn is most in need of influenza/pneumonia medicine

