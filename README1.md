\# Instagram Analytics: SQL \& Python Integration Project



\## Overview

This project demonstrates an end-to-end data analysis workflow using an Instagram Analytics dataset. It combines \*\*SQL\*\* for robust data querying and aggregation with \*\*Python\*\* (Pandas, Seaborn, Scikit-Learn) for data cleaning, exploratory data analysis (EDA), and machine learning predictions.



\## Project Goal

The primary objective is to uncover patterns in Instagram post performance (e.g., best posting times, media types, and account types) and build a predictive model to classify a post's potential performance bucket (low, medium, high, viral) before it is published.



\## Project Structure

```text

instagram\_analytics\_project/

│

├── data/

│   ├── raw/                 <- Original dataset (Instagram\_Analytics.csv)

│   └── processed/           <- Cleaned data exported from Python

│

├── sql/

│   ├── table\_schema.sql     <- SQL table creation scripts

│   └── analysis\_queries.sql <- Advanced SQL queries for data extraction

│

├── notebooks/

│   ├── 01\_data\_cleaning\_and\_prep.ipynb

│   ├── 02\_exploratory\_data\_analysis.ipynb

│   └── 03\_advanced\_analysis\_modeling.ipynb

│

├── src/

│   └── helper\_functions.py  <- Reusable Python functions for EDA and evaluation

│

├── requirements.txt         <- Python dependencies

└── README.md

