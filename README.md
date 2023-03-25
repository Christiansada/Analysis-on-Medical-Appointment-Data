# Investigating the No-Show Appointments Dataset
This repository contains the code and data used to investigate the trends that influence whether or not patients show up for appointments in Brazilian public hospitals. The dataset used in this project was obtained from Kaggle: https://www.kaggle.com/joniarroba/noshowappointments/home.

## Project Overview
The purpose of this project is to explore and analyze the given dataset to answer the following questions:

- What are the behaviorial patterns of patient of the same age group as regards showing for appointments?
- How do patient attend appointments according to the days of the week?
- Does having a scholarship affect whether a patient shows for his appointments or not?
- Does having a Diabetes affect whether a patient shows up for his/her appointments or not?
- Does having gender affect whether a patient shows up for his appointments or not?
The data wrangling process was performed to clean and tidy the dataset before exploration. The exploratory data analysis was carried out using Python libraries such as pandas, numpy, seaborn, and matplotlib.

## Research Question 1: What are the behavioral patterns of patients of the same age group as regards showing for appointments?
To answer this question, the dataset was grouped by age group and the no-show rate was calculated. The results were visualized in a bar plot.

## Research Question 2: How do patients attend appointments according to the days of the week?
To answer this question, the dataset was grouped by appointment day of the week, and the no-show rate was calculated. The results were visualized in a bar plot.

## Research Question 3: Does having a scholarship affect whether a patient shows for his appointments or not?
To answer this question, the dataset was grouped by the presence of a scholarship, and the no-show rate was calculated. The results were visualized in a bar plot.

## Research Question 4: Does having Diabetes affect whether a patient shows up for his/her appointments or not?
To answer this question, the dataset was grouped by the presence of diabetes, and the no-show rate was calculated. The results were visualized in a bar plot.

## Research Question 5: Does having gender affect whether a patient shows up for his appointments or not?
To answer this question, the dataset was grouped by gender, and the no-show rate was calculated. The results were visualized in a bar plot.


## Files
- `noshowappointments-kagglev2-may-2016.csv`: the original dataset obtained from Kaggle
- `investigate-a-dataset.ipynb`: Jupyter Notebook containing the code and analysis for this project
- `README.md`: this file, providing an overview of the project

## Data Wrangling
The data wrangling process involved cleaning and tidying the dataset to prepare it for analysis. This included converting some datatypes to the appropriate format, removing outliers and duplicates, and unifying the column naming convention.

## Exploratory Data Analysis
The exploratory data analysis involved answering the research questions by visualizing and summarizing the data. This was done using various graphs and tables.

## Conclusion
In conclusion, the analysis of the dataset of appointment records for public hospitals in Brazil revealed some interesting findings:

There was no significant difference in the no-show rate for patients of different age groups.
Patients were more likely to show up for appointments that were scheduled on weekdays than on weekends.
Patients with a scholarship were slightly more likely to show up for appointments than those without.
Patients with diabetes were slightly more likely to show up for appointments than those without.
There was a slightly higher no-show rate for male patients than for female patients.
These findings provide useful insights into the factors that influence patient attendance for appointments in Brazil. It is recommended that public hospitals in Brazil schedule more appointments during weekdays than on weekends to encourage more patients to attend their appointments. Additionally, hospitals may want to consider offering more scholarships and targeted outreach programs to encourage patients with diabetes and male patients to attend their appointments.



