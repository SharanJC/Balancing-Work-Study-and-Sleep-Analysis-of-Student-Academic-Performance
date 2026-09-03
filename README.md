# Balancing-Work-Study-and-Sleep-Analysis-of-Student-Academic-Performance

## Project Overview
This project analyses the student performance and study habits dataset to explore how part-time employment may influence students study hours, sleep duration and academic grades. The analysis focuses on identifying patterns and relationships between these factors. Exploratory data analysis, visualizations, correlation analysis, statistical testing, and ordinal logistic modeling that are used to compare students with and without part-time jobs and examine whether work commitments may affect the balance between study, sleep, and academic achievement. 

## Installation & Setup
The repository contains the files required to view and reproduce the analysis:
- R Markdown file (rmd) -> contains R code, analysis, visual graphs, statistical test, and writing analysis
- HTML file -> Contains the completed version of the Markdown Rmd file analysis
- Dataset -> Dataset of students performance & habits

#### 1. Install R 4.6.1
#### 2. Install RStudio
#### 3. Download Project Files
#### 4. Open R Markdown File (rmd)
#### NOTE: Check the dataset file path
#### 5. Generate the HTML Report


## Codes & Resources Used
- **Editor Used:** RStudio
- **Programming Language:** R V 4.6.1
- **Packages Used:**
    - tidyverse
    - dplyr
    - ggplot2
    - MASS
### Dataset Resource
- Name of Dataset: Student Performance & Study Habits
- Dataset Obtained: Kaggle
- Link: [Student Performance & Study Habits Dataset](https://www.kaggle.com/datasets/harshadapatil31/student-performance-and-study-habits-dataset?resource=download)

## Data Preprocessing
The preprocessing stage includes:
- Examine structure of dataset & it's vairables
- Checking: Missing values & Duplicates
- Converting categorical variables into factors where required.
- organizing final grades into an ordered categorical variable
- Preparing variables for statistical analysis & modeling 

## Code Structure
├── Student-Performance-Analysis.Rmd

├── Student-Performance-Analysis.html

├── student-performance-data.csv

└── README.md


## Results and Evaluation

### Exploratory Analysis
includes:
- Distribution of students all four attributes
- Comparison of study hours between students with & without part-time jobs
- Comparison of final grades and part-time job status 
- Visual diagrams comparing, part-time job status of students study hours, sleep hours & finial grades
- Visual diagrams comparing, finial grades of students study & sleep hours

### Spearman Correlation Analysis
Used to examine the strength and direction of relation between selected features. Results identified a correlation of approximately -0.53 for students finial grades to relation of study hours, indicating a moderate negative association, while students sleep duration and final grade produced a weaker correlation of approximately -0.14. 

### T-test Analysis
The t-test compared average study and sleep hours of students with and without part-time employment. The results showed a p-value of 0.5421 for study hours and a p-value of 0.7629 for sleep duration. Since both p-values are greater than 0.05 the test tells us that these was no statistically significant difference in study hours or sleep hours between students with and without a part-time job. 

### Ordinal Logistic Regression
This model was used because the students final grades represent an ordered categorical outcome   
This model allowed the analysis to examine academic performance while preserving the ordered nature of the final grade variables. 

### Conclusion
The overall result concluded that study hours have the strongest relationship with high academic performance, while sleep duration shows a weaker relationship with final grade. Having a part-time job does not appear to have any significant affect on students study hours, sleep duration or final grades. These findings indicates that within the dataset, study habits may play a more important role in academic performance than part-time employment status. However results represent associating within the dataset and should bot be interpreted as evidence of direct causation.

## License
This project is released under the MIT License.

### Dataset License
Source: Kaggle

CC0: Public Domain

