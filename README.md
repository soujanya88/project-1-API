# project-1-API

THE EFFECTS OF AIR QUALITY ON PHYSICAL ACTIVITY AND NUTRITION ANALYSIS IN 2017

Using Air Quality API and Nutrition and Behavioral data (csv file), I chose to analyze the level of air pollutants versus the percent of people engaging in physical activity and nutritional food 
Data size -   csv file - 63,000 rows, 33 columns 

This was filtered down to use only 2017 data since that was the most recent and significant among the ones, we found 
Final csv data file size - 12329 rows × 4 columns

API’s used:
https://dev.socrata.com/foundry/chronicdata.cdc.gov/hn4x-zwk7
https://aqs.epa.gov/data/api/annualData/byState?

https://aqs.epa.gov/aqsweb/airdata/FileFormats.html

CSV File:
Behavioral Risk Factor Surveillance System
https://dev.socrata.com/foundry/chronicdata.cdc.gov/8mrp-rmkw
https://chronicdata.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7

Hypothesis: As the level of air pollutants increases, the percent of people engaging in physical activity and nutritional food decreases. 

The following analysis was done:
Pollutants vs People that are overweight
Pollutants vs People that were Obese
Nitrogen Dioxide vs People that have no Physical Activity
Ozone vs People that had no Physical Activity
Nitrogen Dioxide vs Nutrition
Nitrogen Dioxide vs Higher BMI Level States 


Conclusion: 
Could not prove my hypothesis
Maybe population density was playing a role in air pollution
Pulled in 2017 census data and re-ran the pollution data per capita but found even greater correlations that follow the null hypothesis
Definition of “Health” was determined by the data, could not find on it
Health data was self-reported questions, no measurements were used to confirm the data
Health data did not properly categorize age, ethnicity, income, etc. so we couldn’t use it
Air Pollutant data was from the EPA, who also sets the standards for acceptable levels
Some states have more data points (testing sites) than others
I had to drop some states because there was no data from one of our two source
Looking Forward – analyze more years, include timeline data or air quality
