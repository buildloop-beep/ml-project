# ml-project
READ.md
# Human Activity Recognition Project

This project aims to classify exercise quality using data from wearable sensors. The goal is to predict the quality of exercise based on sensor measurements. The analysis utilizes machine learning techniques, including Random Forests, to predict exercise quality classes (A-E).

## Project Overview

In this project, we use data from sensors attached to participants while they perform different exercise routines. The data is cleaned, preprocessed, and used to train machine learning models to predict exercise quality.

### Key Features:
- **Data Preprocessing**: Includes cleaning of raw sensor data, handling missing values, and removing irrelevant features.
- **Model Development**: A Random Forest classifier is used to predict the exercise quality classes.
- **Model Evaluation**: The model is evaluated using a confusion matrix and cross-validation.
- **Visualization**: Various plots are used to visualize the data distribution, feature importance, and model performance.

## Files in the Repository

```plaintext
/ (root directory)
├── index.html      <- Main report file (generated from `report.Rmd`)
├── README.md       <- This file (project documentation)
├── class_distribution.png  <- Image showing class distribution
├── confusion_matrix.png    <- Confusion matrix plot
├── feature_importance.png   <- Feature importance plot
├── report.Rmd       <- R Markdown file used to generate the HTML report
└── pml-training.csv  <- Training dataset (sensor data)
└── pml-testing.csv   <- Testing dataset (sensor data)
