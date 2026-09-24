# SWYNEX Task 1: Data Preparation

## Overview
This repository contains the data cleaning and preparation pipeline for **Task 1** of the SWYNEX Data Science Internship program. The primary objective of this task is to prepare a raw healthcare/disease prediction dataset by addressing missing values, correcting data types, standardizing column names, and exporting cleaned datasets ready for Exploratory Data Analysis (EDA) and Machine Learning models.

---

## Repository Structure
```text
├── data_preparation.ipynb    # Google Colab notebook containing data processing steps
├── Training_clean.csv        # Processed and cleaned training dataset
├── Testing_clean.csv         # Processed and cleaned testing dataset
└── README.md                 # Project overview and documentation

Dataset & Tools Used
Dataset: Human Disease Dataset (Training.csv & Testing.csv)

Environment: Google Colab

Language: Python 3

Libraries: Pandas, NumPy

Data Cleaning & Processing Steps
Dataset Loading & Inspection: Loaded Training.csv and Testing.csv into Pandas DataFrames and inspected initial shapes, column distributions, and data types.

Missing Value Handling: Checked for null and NaN values across all feature columns to ensure data completeness.

Data Type Verification: Validated integer and categorical data types to ensure consistent formatting across train and test split sets.

Target Label Verification: Verified target disease distributions (e.g., Urinary tract infection, Varicose veins, Hepatitis A) to check class distribution.

Data Export: Saved the final preprocessed datasets as Training_clean.csv and Testing_clean.csv with index preservation disabled (index=False).

Key Assumptions
Missing or null values, if present, are handled without removing critical feature distributions.

Target classes remain balanced across train and test files for optimal model training.

Cleaned CSV outputs preserve feature alignment required for downstream evaluation.

Author & Program Information
Program: SWYNEX Technologies Internship Program

Task: Task 1 - Data Preparation
