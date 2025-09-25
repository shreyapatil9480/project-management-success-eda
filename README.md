
# Project Management Success Analysis

## Overview

This project contains a synthetic dataset and analysis exploring the factors that influence project outcomes. The dataset simulates common attributes of a project such as complexity, team size, budget, duration, risk count, stakeholder engagement, and methodology. Using exploratory data analysis (EDA) and predictive modeling, we investigate how these factors affect cost overruns and on-time completion.

This repository is intended as a portfolio project for Business Analyst, Program Manager, and Data Analyst roles. It demonstrates the ability to generate and work with data, conduct analysis, build visualizations, and apply machine learning models to solve business problems.

## Dataset

The dataset is stored in **`project_management_dataset.csv`** and includes the following columns:

| Column | Description |
| --- | --- |
| `Project_ID` | Unique identifier for each project |
| `Complexity` | Project complexity (`Low`, `Medium`, `High`) |
| `Team_Size` | Number of people in the project team |
| `Budget_K` | Project budget in thousands of dollars |
| `Duration_Months` | Planned project duration in months |
| `Risk_Count` | Number of identified risks for the project |
| `Stakeholder_Engagement_Score` | Engagement score from 1 (low) to 10 (high) |
| `Methodology` | Project management methodology (`Agile`, `Waterfall`, `Hybrid`) |
| `Cost_Overrun_Pct` | Percentage cost overrun at project completion |
| `On_Time_Completion` | 1 if project completed on time, 0 otherwise |

The dataset has 500 rows of sample data.

## Notebook

The Jupyter notebook **`project_management_analysis.ipynb`** walks through the following steps:

1. **Load and Inspect Data** — Load the dataset, preview the first rows, and view summary statistics.
2. **Exploratory Data Analysis (EDA)** — Explore distributions of cost overruns, examine on-time completion rates across categories, and visualize correlations between numeric features.
3. **Predictive Modeling** — Build a logistic regression model to predict whether a project will be completed on time based on features such as complexity, team size, budget, duration, risks, engagement, and methodology. The model pipeline includes one-hot encoding for categorical variables and uses an 80/20 train-test split.
4. **Evaluation** — Evaluate model performance using accuracy and a classification report.

## Requirements

All dependencies for this project are listed in **`requirements.txt`**. To set up and run the notebook locally:

```bash
pip install -r requirements.txt
jupyter notebook project_management_analysis.ipynb
```

## Usage

This project is fully self-contained and ready to run. You can reproduce the analysis or extend it further by experimenting with different models, tuning hyperparameters, or adding new features. Feel free to fork the repository and adapt the project to your own needs.

## License


This project is released under the MIT License. You are free to use, modify, and distribute it.

## Notes
This project was created as a demonstration of data analysis and machine learning skills for prospective employers. The synthetic data allows you to test exploratory analysis, visualization, feature engineering, and predictive modeling techniques. Feel free to explore alternative models, add additional analyses, or integrate this work into your own portfolio.




## Notes
This project was created as a demonstration of data analysis and machine learning skills for prospective employers. The synthetic data allows you to test exploratory analysis, visualization, feature engineering, and predictive modeling techniques. Feel free to explore alternative models, add additional analyses, or integrate this work into your own portfolio.released under the MIT License. You are free to use, modify, and distribute it.
