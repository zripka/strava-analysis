library(tidyverse)

strava_data <- read_csv('C:/Users/zripk/documents/data/strava/21-12-19-strava-archive/activities.csv')

# How many columns are there in this dataset?
strava_data

# What are the names of all the columns?
colnames(strava_data)

# Limiting the dataset to only columns I care about
strava_data <- select(strava_data,
                      "Activity ID", 
                      "Activity Date", 
                      "Activity Name", 
                      "Activity Type",
                      "Activity Description",
                      "Elapsed Time",
                      "Distance",
                      "Relative Effort",
                      "Commute",
                      "Moving Time",
                      "Max Speed",
                      "Average Speed",
                      "Elevation Gain",
                      "Elevation Loss",
                      "Elevation Low",
                      "Elevation High",
                      "Number of Runs",
                      "Uphill Time",
                      "Downhill Time",
                      "Other Time",
                      "Perceived Exertion",
                      "Total Weight Lifted")