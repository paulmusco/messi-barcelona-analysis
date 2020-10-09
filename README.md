# messi-barcelona-analysis

## Project Description 
Analyse FC Barcelona during the Lionel Messi era.

## Data
Sourced from Statsbomb's (https://statsbomb.com/) open data github repository. The data came in the form of hundreds of JSON files, which I can combined into CSV files (competitions.csv, matches.csv, events.csv, lineups.csv). The original JSON files and all CSV files created can be found here - https://drive.google.com/drive/u/0/folders/1g76yuSsOAeZOpyonhNRyGPxocogRZkE3 

## Workflow
- Source data
- Combine hundreds of JSON files into CSV files
- Clean and manipulate data in CSV files
- Data exploration
- Data analysis (Correlation, linear regression, quadratic regression)
- Data visualisation
- Machine learning (supervised, logistical regression)
- Tableau visualisations
- Prepare presentation

## Notebooks
initial_data_import_cleaning_manipulation - convert JSON files to CSV
cleaning_events_dataset - further cleaning/splitting
cleaning_function_testing - testing function in above notebook
messi_output_prep - preparing data for Tableau
messi_output_analysis - linear regression
influential_players - no correlation (but needed to create the messi_starts CSV file)
machine_learning_shot_classification - supervised machine learning
location_visualisation_prep - logistic regression data preparation for Tableau
correlation - looking for correlation between variables & results/Messi output & preparation for Tableau

## Presentation
https://docs.google.com/presentation/d/1WhH0NE-0t0Bxpb4gQyTfhsHFT5Be0Q44suDJuYD-28Y/edit#slide=id.p

## Tech Stack
Python
Pandas
Numpy
Matplotlib
Seaborn
Jupyter Notebook
Tableau
