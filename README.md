# Diabetes Dataset Analysis with Random Forest with and without SMOTE

## Overview

This repository contains a Python project aimed at analyzing a diabetes dataset using machine learning techniques and data visualization tools. The project focuses on applying Random Forest algorithms, both with and without SMOTE (Synthetic Minority Over-sampling Technique) for balancing the dataset, to identify patterns and gain valuable insights into diabetes prevalence and associated risk factors.

## Dataset

The dataset comprises various health indicators and demographic details of individuals, including:
- Diabetes status (binary)
- General health condition
- Physical activity levels
- Education and income levels
- Health behaviors such as smoking and alcohol consumption

## Project Structure

- `Data_quality_Check_and_Mapping.py`: Python script for initial data preprocessing and quality checks.
- `random_forest_analysis.py`: Python script applying Random Forest with and without SMOTE.
- `tableau_analysis`: Folder containing Tableau workbooks for interactive data visualization.
- `README.md`: This file, providing an overview and instructions for the project.

## Setup

To set up the project, ensure you have the following dependencies installed:

- pandas
- numpy
- scikit-learn
- imbalanced-learn (for SMOTE)
- matplotlib
- seaborn

You can install these using pip:

```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
