# Law_School_Outcomes
Dashboard visualization of ABA employment data

## ABA_downloads

This folder contains download of ABA employment data stored in Excel files from https://www.abarequireddisclosures.org/employmentoutcomes.aspx. The data were downloaded on 5/18/2022 between 10:44AM and 10:36AM, exept for "Employment Summary_2022.xlsx" file, which was downloaded 5/23/2022 at 6:18PM.

## Data cleaning scripts

The "employment_overall_cleaning", "employment_type_cleaning", and "top_states" Jupyter notebooks use the ABA datasets to create three tidy datasets of the overall employment numbers (top table of ABA reports), employment numbers by type (second table of ABA reports), and top states by employer, respectively. 

## consolidated_data_long

This folder contains the output of the jupyter notebooks from the cleaning scripts as csv files.

## dashboard_interactive

This script creates a dash dashboard using the data from the "consolidated_data_long" folder. Note that this script creates a local version of the dashboard and does not deploy it online. For deployment, I used the Heroku and PyCharm in line with the instrucitons here: https://www.youtube.com/watch?v=Gv910_b5ID0.
