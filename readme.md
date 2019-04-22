# Exploring Ford GoBike 2018  

## Overview
This excercise makes exploratory and explanatory analyses from the Ford GoBike 2018 datasets found in https://s3.amazonaws.com/fordgobike-data/index.html.

The main target is to find any relationships between the user types (customers and subscriptors) and other variables: ride duration, start and end stations, age of the riders, and time of the year.

## Technologies
* Python
** numpy, pandas, matplotlib, seaborn

## Key findings
Two profiles were defined for customers and subscriptors, which include their age, minutes spent by ride, frequented areas, their use throughout the year, and peak usage. 

## Files

- Rides_exploratory.ipynb
  Jupyter notebook with the exploratory process of the 12 csv files of 2018 trip data

- Rides_explanatory.ipynb
  Jupyter notebook with the explanatory process, and where the slides for the presentation were selected

- output-toggle.tpl
  file needed to avoid showing code in the slides

- Rides_explanatory.slides.html
  the slides file

- jpg and png images

If you want to see the slides in action, run:

jupyter nbconvert Rides_exploratory.ipynb --to slides --post serve --template output-toggle.tpl



