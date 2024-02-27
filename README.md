# nosql-challenge
Module 12 Challenge

## Context
This project analyzes food hygiene ratings of eating establishments in the United Kingdom. Data is provided by the UK Food Standards Agency.

## Execution
1) Import the dataset into MongoDB with the following command line command:<br>
mongoimport --type json -d uk_food -c establishments --drop --jsonArray Resources/establishments.json
2) Run the NoSQL_setup.ipynb notebook to clean and format the data.
3) Run the NoSQL_analysis.ipynb notebook to view the query results used in the analysis.
