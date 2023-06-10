# Powerlifting-ipf-Analysis
Analysis of IPF powerlifting Competitions

This repository contains the code and analysis for performing data analysis on powerlifting data. The analysis includes data collection, data cleaning, and exploratory data analysis to gain insights into the sport of powerlifting.

# Data Collection
The data for this analysis was collected from the International Powerlifting Federation (IPF) and the OpenPowerlifting databases. The data includes information about powerlifting competitions, lifters, their lifts, and various other attributes.

The data collection process involved downloading the dataset from here [https://openpowerlifting.gitlab.io/opl-csv/bulk-csv.html](url)

# Data Cleaning
Data cleaning is an essential step to ensure the accuracy and reliability of the analysis. The following data cleaning steps were performed:

* Handling Missing Values:

  Identified missing values in the dataset.
  Decided whether to remove the rows with missing values or impute the missing values using appropriate techniques.
Removing Duplicates:

* Checked for duplicate entries in the dataset.
  Removed duplicate rows or kept only the unique entries.
* Standardizing Data:

  Ensured consistency in the data by standardizing variables, such as unit conversions or date formats.
* Data Transformation:

  Performed necessary transformations, such as converting categorical variables to numerical representation or creating new derived variables.
  
# Exploratory Data Analysis
Exploratory Data Analysis (EDA) is conducted to understand the characteristics and patterns in the data. The following analyses were performed:

Summary Statistics:

Calculated descriptive statistics to summarize the main characteristics of the data.
Computed measures such as mean, median, standard deviation, and quartiles.
# Data Visualization:

* Created various plots and visualizations to understand the distributions, relationships, and trends in the data.
  Utilized bar plots, line plots, scatter plots, histograms, and box plots to visualize the data.
  Performance Analysis:

*Analyzed the performance of lifters based on various factors such as weight class, equipment used, and country.
  Investigated the highest total weight lifted and identified standout performers in each weight class.
* Time Trend Analysis:

  Explored the performance of lifters over time to identify any noticeable trends or improvements.
  Examined changes in total weight lifted, number of participants, and other performance metrics over different years.
* Equipment Usage Analysis:

  Examined the distribution of lifters using different types of equipment (e.g., raw, equipped).
  Investigated if there were any performance differences based on the type of equipment used.
* Dots Analysis:

  Explored the relationship between Dots (a powerlifting scoring system) and the lifters' performance.
  Investigated whether higher Dots scores were associated with higher total weights lifted.
# Conclusion
* Through the data collection, cleaning, and analysis process, valuable insights were gained into the sport of powerlifting.
* The analysis helped understand factors influencing performance, identify standout performers, and uncover trends over time. 
* The results provide a foundation for further analysis and research in the field of powerlifting.

Please refer to the respective Jupyter Notebook or Python scripts in this repository for detailed code implementation and further information on each step of the analysis.
