# Basic Data Analysis in Banking Sector
This project is a simple data analysis project that explores a dataset from the banking sector. The goal of this project is to provide some insights into the dataset and to demonstrate some basic data analysis techniques using Python.

# Dataset
The dataset used in this project is the "bank.csv" dataset from the UCI Machine Learning Repository. It contains information about bank customers and their characteristics, as well as whether or not they subscribed to a term deposit. The dataset has 41,188 rows and 21 columns.

# Tools Used
This project uses the following tools and libraries:

Python 3.7
Pandas
NumPy
Matplotlib

# Analysis
The following analyses were performed on the dataset:

A general look at the DataFrame using df.
A summary of the dataset, including column data types and non-null values, using df.info().
Counting the number of missing values in each column of the dataset using df.isnull().sum().
Generating a statistical summary of the dataset's numerical features using df.describe().
Counting the number of term deposit subscriptions and non-subscriptions in the dataset using df["y"].value_counts().
Visualizing the distribution of term deposit subscriptions in the dataset using df["y"].value_counts().plot(kind = "bar").
Looking for the term deposit subscription distribution according to age using df.boxplot(column = "age", by = "y").
Generating a correlation matrix and visualizing it as a heatmap using corr_matrix = df.corr() and plt.matshow(corr_matrix).

# Conclusion
Overall, this project provides a basic introduction to data analysis using Python and demonstrates some common techniques that can be used to explore a dataset. By analyzing the bank dataset, we were able to gain some insights into customer characteristics that may influence their decision to subscribe to a term deposit.
