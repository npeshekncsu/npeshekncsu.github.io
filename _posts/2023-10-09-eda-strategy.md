# Strategy for doing Exploratory Data Analysis (EDA)

## What is EDA and goal of the EDA

EDA is a important initial step in the machine learning, statistical inference and data analysis. It involves systematically examining and visualizing datasets to gain insights, discover patterns, and uncover potential relationships among variables. The goal of the EDA is to understand the structure and characteristics of data sets, identify outliers, missing values, and anomalies, and assess the assumptions of statistical models. Using techniques such as data visualization, summary statistics, and data transformation, EDA aims to provide a comprehensive overview of the data, guiding subsequent data modeling and hypothesis testing. It is an essential tool for making informed decisions, generating hypotheses, and ultimately deriving meaningful conclusions from complex datasets.

## EDA strategy


In order to conduct a proper EDA, the steps described below are important.

**1. Data Cleaning**


  - Understand missing values in the data set
  - Address missing values by imputing them or removing rows/columns with missing data (removing missing data is usually not recommeded but in case of large data set or small percentage of missing values, this approach is accepatble)
  - Standardize or normalize numerical variables if needed to ensure consistency

**2.Summary Statistics**


Calculate basic statistics:

  - Mean, median, variance, quantiles, standard deviation for numerical variables
  - Frequency counts for categorical variables

**Data Visualization**

Create visualizations to explore data distributions and relationships:


  - Histograms and density plots for numerical variables
  - Box plots to identify outliers and assess data spread
  - Scatter plots to visualize relationships between pairs of variables
  - Bar charts for categorical variables

**Explore Relationships between variables**
  - Compute correlation matrices to measure relationships between numerical variables
  - Create heatmaps to visualize correlations
  - Use pair plots to explore pairwise relationships


**Feature Engineering**
  - Generate new features based on domain knowledge or identified patterns
  - Create dummy variables for categorical variables

**Dimensionality Reduction**
  - Apply dimensionality reduction techniques like Principal Component Analysis (PCA) to reduce the number of variables, if needed.
  - Visualize data in lower-dimensional spaces

## Wrap up

The goal of EDA is to gain a deep understanding of the dataset, identify patterns and outliers, select appropriate features for modeling, and inform data-driven decisions. It is a crucial step in the data analysis process, setting the foundation for subsequent modeling and hypothesis testing.


