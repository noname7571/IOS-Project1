# Corona Data Analyzer

## About
Author: Matej Tomko  
Date: 2022-04-01  

## Overview
This project is a simple data analyzer for COVID-19 records. It provides various commands to analyze and visualize COVID-19 data stored in CSV files.

## Usage
```bash
corona [-h] [FILTERS] [COMMAND] [LOG [LOG2 [...]]
```

## Commands
- `infected`: Count the number of infected individuals.  
- `merge`: Merge multiple log files into one, preserving the original order.  
- `gender`: Display the count of infected individuals for each gender.  
- `age`: Display statistics on the number of infected individuals based on age.  
- `daily`: Display daily statistics of infected individuals.  
- `monthly`: Display monthly statistics of infected individuals.  
- `yearly`: Display yearly statistics of infected individuals.  
- `countries`: Display statistics of infected individuals for each country.  
- `districts`: Display statistics of infected individuals for each district.  
- `regions`: Display statistics of infected individuals for each region.

## Filters
- `a DATETIME`: Consider only records after the specified date (format: YYYY-MM-DD).  
- `b DATETIME`: Consider only records before the specified date (format: YYYY-MM-DD).  
- `g GENDER`: Consider only records of individuals with the specified gender (M or Z).  
- `s [WIDTH]`: Display data graphically using histograms (optional WIDTH parameter).

## License
This project is licensed under the MIT License.
