# Titanic Data Visualization Dashboard

## Project Overview
This project is part of the Data Science with Python Internship (Task 4). It features a mini-dashboard that explores the Titanic dataset to identify patterns in passenger demographics and survival rates.

## Dataset
The project uses the **Titanic** dataset loaded directly via the `seaborn` library. 
- **Features used:** Age, Sex, Class, Fare, SibSp, Parch.
- **Created Features:** `FamilySize` and `AgeGroup`.

## Visualizations Included
1. **Histogram:** Distribution of passenger ages.
2. **Bar Chart:** Survival rates compared by gender.
3. **Boxplot:** Fare distribution across different passenger classes.
4. **Scatterplot:** Relationship between Age and Fare, highlighted by survival status.
5. **Heatmap:** Correlation matrix of numerical variables.

## How to Run
1. Ensure you have Python installed.
2. Install dependencies: `pip install pandas numpy seaborn matplotlib`.
3. Open `titanic_dashboard.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells. Images will be automatically saved in the `/images` folder.
