# Zoho Workplace Analysis: Is Zoho a Good Company?

This project aims to determine whether **Zoho** is considered a good company for employees based on employee satisfaction data. Using a **Decision Tree Classifier**, the project predicts whether an employee views Zoho as a good company based on several workplace factors.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Algorithm](#algorithm)
- [Why Decision Tree?](#why-decision-tree)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)

## Project Overview

The goal of this project is to predict whether Zoho is perceived as a good company by its employees. This is framed as a **binary classification problem** using various employee satisfaction features as inputs and the `Zoho_Good_Company` column as the target.

### Input Features:
- **Workspace_OK**: Satisfactory workspace (1 for Yes, 0 for No)
- **Internet_OK**: Adequate internet connectivity (1 for Yes, 0 for No)
- **System_Resource_OK**: Sufficient system resources (1 for Yes, 0 for No)
- **Team_OK**: Satisfied with team environment (1 for Yes, 0 for No)
- **Skill_Improvement**: Skill improvement at the company (1 for Yes, 0 for No)
- **Salary_OK**: Satisfied with salary (1 for Yes, 0 for No)
- **Lunch_OK**: Happy with lunch services (1 for Yes, 0 for No)
- **Parking_OK**: Satisfied with parking facilities (1 for Yes, 0 for No)
- **Restroom_OK**: Adequate restroom facilities (1 for Yes, 0 for No)
- **Air_Ventilation_OK**: Good air ventilation (1 for Yes, 0 for No)

### Target Variable:
- **Zoho_Good_Company**: Indicates whether employees consider Zoho a good company (1 for Yes, 0 for No).

## Algorithm

We use a **Decision Tree Classifier** to predict the target variable. This algorithm was chosen for its:
- **Interpretability**: Easy to understand and visualize.
- **Handling non-linearity**: Can handle complex, non-linear relationships.
- **Minimal data preparation**: No need for feature scaling or normalization.
- **Suitability for small datasets**: Works well with small datasets.

## Why Decision Tree?

1. **Simplicity**: It is simple and intuitive to explain the decision-making process.
2. **Flexibility**: Handles both categorical and numerical data effectively.
3. **Minimal preprocessing**: It requires minimal feature engineering or data transformation.
4. **Overfitting control**: Hyperparameters like tree depth can be fine-tuned to avoid overfitting.

