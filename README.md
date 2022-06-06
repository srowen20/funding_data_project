# Investment Data Project
Project to visualise, analyse and predict the amount raised in funding rounds of companies around the world. 

predictor = 'raised_amount_usd'

features include funding round type, continent, date founded, date funded, status of company and sector.

## File and Folder Locations

The data files required for the project are found in the main directory and are called:
- companies.txt
- investment_rounds.csv
- mapping.csv

## Running the Code

The code must be run in the following order:
1. SO_Pre-Processing
2. SO_Analysis
3. SO_ML

There are breakpoints in the code where the Dataframes are saved as a checkpoint. You can choose to save these and reload them or skip them and continue through the code. Therefore, avoid 'run all' where possible. 

Ensure the following packages are installed on your laptop/computer:
- pandas
- numpy
- matplotlib
- seaborn
- pycountry
- math
- requests
- geopy
- sklearn 
