# Data_Cleaning_-Flight-Price-Prediction-
✈️ Flight Price Prediction – Data Cleaning
📌 Project Overview

This repository contains the data cleaning and preprocessing pipeline for a Flight Price Prediction project.
The goal of this stage is to transform raw flight data into a clean, structured, and model-ready dataset suitable for machine learning algorithms.

Flight price data often contains missing values, inconsistent formats, categorical variables, and outliers. This project focuses on handling these issues systematically to improve prediction accuracy in later stages.

📂 Dataset Description

The dataset includes information related to commercial flights such as:

 Airline name

 Source city

 Destination city

 Date of journey

 Departure and arrival time

 Flight duration

 Number of stops

 Ticket price (target variable)

The raw dataset is assumed to be noisy and unstructured, requiring extensive preprocessing.


🧹 Data Cleaning Steps Performed
1️⃣ Handling Missing Values

Checked for null or empty values in all columns

Removed rows with critical missing information (e.g., price)

Imputed or discarded non-essential missing values when appropriate


2️⃣ Feature Formatting & Transformation

Converted date columns into proper datetime format

Extracted useful features such as:

Day

Month

Converted duration into numerical format (total minutes)

Standardized time formats for departure and arrival times


3️⃣ Categorical Data Processing

Cleaned inconsistent text values (extra spaces, capitalization issues)

Encoded categorical variables like:

Airline

Source

Destination

Number of stops

Used label encoding / one-hot encoding depending on feature type


4️⃣ Outlier Detection & Removal

Identified extreme values in ticket prices

Removed or capped unrealistic price values to reduce model bias


5️⃣ Duplicate Records

Detected and removed duplicate rows to prevent data leakage


6️⃣ Final Dataset Preparation

Verified data types for all columns

Ensured no missing values remained



🛠️ Technologies Used

Python

Pandas

NumPy


🚀 Next Steps

After data cleaning, the next phases include:

Exploratory Data Analysis (EDA)

Feature Engineering

Model Training

Model Evaluation

Deployment
