✈️ Flight Price Prediction – Data Cleaning

Data_Cleaning_-Flight-Price-Prediction

📌 Project Overview

This repository contains the data cleaning and preprocessing pipeline for a Flight Price Prediction project.
The primary objective of this stage is to convert raw, unstructured flight data into a clean, consistent, and machine-learning-ready dataset.

Real-world flight price datasets often suffer from missing values, inconsistent formats, noisy categorical variables, and outliers. This project systematically addresses these issues to ensure high-quality input data for downstream modeling tasks and improved prediction performance.



📂 Dataset Description

The dataset consists of information related to commercial airline flights, including:

✈️ Airline name

🌍 Source city

🏁 Destination city

📅 Date of journey

⏰ Departure and arrival times

⌛ Flight duration

🔁 Number of stops

💰 Ticket price (target variable)

The raw dataset is assumed to be noisy and inconsistent, requiring extensive preprocessing before it can be used for predictive modeling.



🧹 Data Cleaning Steps Performed
1️⃣ Handling Missing Values

Identified null and empty values across all features

Removed rows with missing critical information (e.g., ticket price)

Imputed or safely discarded non-essential missing values where applicable



2️⃣ Feature Formatting & Transformation

Converted date columns into proper datetime format

Extracted meaningful temporal features:

Day

Month

Transformed flight duration into a numerical format (total minutes)

Standardized departure and arrival time formats



3️⃣ Categorical Data Processing

Cleaned inconsistent text data (extra spaces, casing issues)

Encoded categorical variables such as:

Airline

Source

Destination

Number of stops

Applied Label Encoding or One-Hot Encoding based on feature characteristics



4️⃣ Outlier Detection & Removal

Analyzed ticket price distribution to detect extreme values

Removed or capped unrealistic prices to minimize model bias



5️⃣ Duplicate Records Handling

Identified and removed duplicate entries

Ensured data integrity and prevented data leakage



6️⃣ Final Dataset Preparation

Verified correct data types for all columns

Ensured the dataset contained no missing values

Prepared the final cleaned dataset for:

Exploratory Data Analysis (EDA)

Feature engineering

Model training



🛠️ Technologies Used

Python

Pandas

NumPy

🚀 Next Steps

Following the data cleaning phase, the project will proceed with:

📊 Exploratory Data Analysis (EDA)

🧠 Feature Engineering

🤖 Model Training

📈 Model Evaluation

🌐 Deployment
