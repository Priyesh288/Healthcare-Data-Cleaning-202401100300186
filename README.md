Healthcare Data Cleaning

Overview

This Python script efficiently cleans healthcare data to ensure accuracy and reliability for analysis. It follows a structured process that handles missing values, standardizes data, and prepares it for further insights.

Features

Handles missing values with forward fill for continuous data.

Removes duplicate entries to maintain data integrity.

Standardizes column names for consistency.

Converts date columns like date_of_birth into proper datetime format.

Filters out outliers in the age column (keeping values between 0 and 120).

Encodes categorical variables such as gender into numerical format (Male = 1, Female = 0, Unknown = -1).

Requirements

Python 3.x

Pandas library
