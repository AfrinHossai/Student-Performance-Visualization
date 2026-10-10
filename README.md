# Student Performance Analysis and Prediction
An interactive data visualization and machine learning project analyzing factors associated with student academic performance.


# Author
Afrin Hossain

## Project Description

I aim to analyze student academic performance and investigate how factors such as study time, attendance, parental education, and previous grades are associated with students' final grades. I will use the Student Performance dataset from the UCI Machine Learning Repository, focusing on 649 student records from Portuguese-language courses in two secondary schools in Portugal. Python libraries such as pandas, Matplotlib, Seaborn, and Plotly will be used to clean, analyze, and visualize the dataset to identify meaningful patterns. An interactive dashboard will be developed using Streamlit to allow users to explore academic performance across different student characteristics. Additionally, I plan to use some machine learning models such as Linear Regression and Random Forest to predict final grades, evaluate prediction accuracy, and discuss potential biases and limitations.

Here is the link of dataset.
https://archive.ics.uci.edu/dataset/320/student+performance


## Project Outline / Plan

### Interface Plan

I plan to develop an interactive web-based dashboard using Streamlit and Plotly to help users explore student academic performance. The dashboard will include an overview of the dataset, visualizations showing relationships between student characteristics and final grades, and a machine learning prediction section. Users will be able to filter the data by factors such as school, study time, and previous academic performance to compare different student groups. Interactive charts will include hover information, clear labels, and accessible colors to make the findings easier to understand. The interface will be designed with simple navigation so that students, teachers, and other interested users can explore the data and understand the results.


### Data Collection and Storage Plan

I will use the Student Performance dataset from the UCI Machine Learning Repository, which contains academic, demographic, social, and school-related information collected from two secondary schools in Portugal. For this project, I will focus on the `student-por.csv` file, which contains 649 student records and 33 columns. I have downloaded the dataset and will use Python and pandas to load it, inspect data types, check for missing values and duplicates, and identify any invalid or inconsistent values. Although the dataset is reported to have no missing values, I will verify its quality independently and document all cleaning and preprocessing decisions. I will keep the original CSV file separate from the cleaned dataset and organize my work into folders for data, notebooks, visualizations, and reports. I will use GitHub to maintain version control for my code and documentation, while excluding local data files through `.gitignore` and providing instructions to download the original dataset for reproducibility.




### Data Analysis and Visualization Plan

I plan to analyze the Student Performance dataset using Python libraries such as pandas, NumPy, Matplotlib, Seaborn, and Plotly. First, I will perform exploratory data analysis (EDA) to understand the distribution of final grades and investigate relationships between academic performance and factors such as study time, absences, parental education, and previous grades. I will calculate descriptive statistics, examine correlations, and perform at least one appropriate statistical hypothesis test to determine whether meaningful differences exist between student groups.

I will create at least five static visualizations, including a histogram of final grades, a box plot comparing grades across study-time groups, a scatter plot showing absences versus final grades, a bar chart comparing performance across parental education levels, and a correlation heatmap. Each visualization will include clear labels, accessible colors, and an explanation of the chart choice and its potential limitations.

I will also develop interactive visualizations using Plotly and Streamlit so users can filter student groups and explore patterns dynamically.

For the machine learning component, I plan to use Linear Regression and Random Forest Regression to predict students' final grades (`G3`). I will divide the dataset into training and testing sets and evaluate model performance using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²). I will also compare predictions with and without previous grades to better understand how different variables affect predictive performance.

Finally, I will summarize my findings, explain the limitations of the dataset, discuss potential biases, and present the results in a final report and presentation.
 
