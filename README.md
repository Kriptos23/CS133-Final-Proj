# CS133-Final-Proj
# UFC dataset and fight outcome analysis

## Authors

- Daniel Kuvanychbekov

## Project Description

We will investigate over UFC dataset and try to analyse historical UFC fights to find how weight class and fighting style relate to fight outcomes. We will examine variables such as winner, weight class, method of victory, significant strikes, takedowns, submission attempts, and fight duration. Our analysis will identify patterns in how UFC fights end across different divisions and time periods. We will create statistical summaries and visualizations to compare knockouts, submissions, and decisions. The final project will present the results through a written report, static visualizations, and an interactive dashboard.

Possible investigations:

1. How do weight class, fighting style, and fight duration relate to UFC fight outcomes?
2. Which weight classes have the highest percentage of knockouts, submissions, and decisions?
3. Do longer fights more often end in decisions?
4. Are takedowns, significant strikes, or control time associated with winning?
5. Have UFC fight-ending methods changed over time?
6. Do striking-heavy or grappling-heavy fighters win more often?
7. Does the height and arm reach give advantage in the fight?

## Project Outline

### Interface Plan

We plan to create an interactive dashboard that allows users to filter UFC fights by weight class, year, and method of victory. The dashboard will display charts showing win methods, fight duration, striking statistics, and takedown statistics. Users will be able to compare different divisions and explore how fight outcomes vary across the dataset.

### Data Collection and Storage Plan

We will collect UFC fight data from UFCStats.com. The data will include fight dates, weight classes, fighter names, fight outcomes, methods of victory, round, fight time, significant strikes, takedowns, submission attempts, and control time. The original data will be stored in the `data/raw/` directory without modification. After cleaning missing values, duplicate rows, and inconsistent labels, the cleaned dataset will be stored as a CSV file in the `data/cleaned/` directory. Python and pandas will be used for data collection, cleaning, and storage.

### Data Analysis and Visualization Plan

We will calculate descriptive statistics for fight duration, significant strikes, takedowns, and submission attempts. We will compare fight outcomes across weight classes and examine whether fight duration differs between knockouts, submissions, and decisions. We will use bar charts, histograms, box plots, and time-series charts to communicate the main findings. We will also perform at least one statistical test, such as a chi-square test examining the relationship between weight class and method of victory. We will discuss limitations, missing data, possible bias, and whether the visualizations could lead to misleading conclusions.





