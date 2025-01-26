# Data Analysis and Trading Strategy 

### Overview

This task involves analyzing power market data and developing a trading strategy based on wind and solar power forecasts. The goal is to explore the relationship between renewable energy production and electricity prices and to design a profitable trading strategy using Day-Ahead and Intraday markets.

### Data Source

The dataset used to load the data into the projet was the "analysis_task_data.xlsx", but it was cleaned and preprocessed to "cleaned_file.xlsx".

### Data Preprocessing

- The file was loaded and the sheets were checked
- The main dataset from the "DE_Wind_PV_Prices" sheet was loaded and the data was checked
- To figure out if the formatting of the columns was okay, and info function was run 
- The cleaned dataset was then extracted to a different Excel file to be used

### Task Breakdown

#### Task 2.1

- Calcualting the Aggregate total energy production for Wind and PV (solar) in MWh
- Ensure the conversion from MW to MWh is made as it is in quarter-hourly format 

#### Task 2.2

- Calculated the average Wind and PV production for 2021 over a 24h period for Intraday and Day Ahead
- Graphed the results

#### Task 2.3

- Calculated the average Wind, PV, and total revenue
- Showed what the difference between Wind, PV, and total revenue was

#### Task 2.4

- Calculated the day with the highest and lowest energy production
- Compared them and analyzed price differences

#### Task 2.5

- Calculated the average hourly DA price on weekdays and weekends
- Compared them and explained why there was a difference

#### Task 2.6

- Calculated the revenue for a battery with a capacity of 1 MWh which is fully charged and discharged once per day
- Determined what would be the best time to charge and discharge the battery and produce the most amount of revenue

### Task 2.7

- Designed a Trading Strategy to make money between the DA and ID market
- Visualized and explained the Trading Strategy