# SECT-4451: Lecture 2 Practical
## Data Exploration and Foundational Math

### 1. Project Overview

This practical focuses on exploring, cleaning, summarizing, and visualizing a student performance dataset using Python. It also introduces foundational mathematical concepts used in machine learning, including correlation, vectors, dot products, and feature scaling.

### 2. Objectives

The main objectives of this practical are to:

- Explore a dataset using Pandas and NumPy.
- Identify and handle outliers, missing values, and invalid values.
- Calculate the mean, median, and standard deviation.
- Visualize data using histograms and scatter plots.
- Calculate the Pearson correlation coefficient.
- Understand the relationship between correlation and causality.
- Represent student features as vectors and calculate dot products.
- Standardize numerical features for machine-learning algorithms.

### 3. Technologies and Libraries

The practical uses the following tools:

- **Python** — programming language for data analysis.
- **Jupyter Notebook** — environment for writing and executing Python code.
- **Pandas** — data manipulation and analysis.
- **NumPy** — numerical calculations and mathematical operations.
- **Matplotlib** — data visualization.

### 4. Dataset Description

The dataset contains 100 student records and four numerical columns:

| Column | Description |
|---|---|
| `study_hours` | Number of hours a student studies |
| `attendance` | Student attendance percentage |
| `previous_mark` | Student's previous academic mark |
| `final_score` | Student's final score |

The dataset was generated using Python and NumPy for educational purposes.

### 5. Practical Tasks

#### Part A: Inspect and Clean
- Inspected the dataset's structure, dimensions, and missing values.
- Identified an outlier in `study_hours`.
- Handled missing study-hour values and an invalid negative attendance value.
- Selected input features and the target variable.

#### Part B: Summarize
- Calculated the mean, median, and standard deviation of all numerical columns.
- Interpreted the statistical results in plain English.

#### Part C: Visualize
- Created a histogram to examine the distribution of final scores.
- Created a scatter plot to explore the relationship between study hours and final scores.

#### Part D: Correlation and Causality
- Calculated the Pearson correlation coefficient between study hours and final scores.
- Discussed why correlation does not guarantee a specific score or prove causation.
- Identified possible confounding variables.

#### Part E: Vectors and Dot Product
- Represented one student's input features as a NumPy vector.
- Defined a weight vector and bias.
- Calculated a predicted output using the dot product.

#### Part F: Scaling
- Standardized `study_hours` and `previous_mark`.
- Explained why scaling is important for distance-based algorithms such as K-Nearest Neighbors (KNN).

### 6. Conclusion

This practical provided hands-on experience with the foundational steps of data analysis and machine learning. It demonstrated how data cleaning, statistical summaries, visualization, correlation, vector operations, and standardization help prepare data for further analysis and predictive modeling.


