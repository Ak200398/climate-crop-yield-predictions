# Harnessing Climate Data for Accurate Crop Yield Predictions

## Overview

Food security is a pressing global challenge, and with the impact of climate change, predicting crop yields has become increasingly complex. This project leverages advanced data analytics and machine learning to develop accurate crop yield predictions using climate data. The goal is to assist farmers, policymakers, and agricultural strategists in making informed decisions to ensure food security and optimize agricultural practices.

---

## Project Features

- **Exploratory Data Analysis (EDA):** Understanding relationships between climate variables and crop yields.
- **Statistical Analysis:** Performing t-tests and ANOVA to determine significant features.
- **Predictive Modeling:** Using Multi-Linear Regression and Random Forest models to forecast crop yields.
- **Data Visualization:** Creating heatmaps, violin plots, and feature importance charts to present findings.
- **Insightful Results:** Offering actionable insights for stakeholders in agriculture.

---

## Dataset Description

The dataset used in this project consists of:

- **Area:** Geographical regions.
- **Item:** Crop types (e.g., maize, potatoes).
- **Year:** Temporal data from 1990 to 2013.
- **hg/ha\_yield:** Crop yield (hectograms per hectare).
- **average\_rain\_fall\_mm\_per\_year:** Average rainfall.
- **pesticides\_tonnes:** Amount of pesticides used.
- **avg\_temp:** Average temperature.

**Dataset Location:** The dataset is stored in the `data/` folder.

---

## Technologies Used

- **Python Libraries:**
  - pandas and numpy for data manipulation.
  - matplotlib and seaborn for visualization.
  - scikit-learn for machine learning models.
- **Statistical Tools:**
  - t-tests and ANOVA for feature selection.
- **Google Colab:** Environment for development and execution.

---

## Repository Structure

```
climate-crop-yield-predictions/
├── data/
│   ├── yield_df.csv            # Dataset file
│   ├── README.md              # Description of the dataset
├── notebooks/
│   ├── Implementation.ipynb         # Jupyter notebook with code and analysis
└── README.md                  # Main project readme
```

---

## Key Visualizations

1. **Correlation Heatmap:**

   - Highlights relationships between numerical variables like temperature, rainfall, and yield.

2. **Violin Plots:**

   - Shows yield distributions across different crop types and regions.

3. **Feature Importance:**

   - Bar chart from Random Forest highlighting critical factors like pesticide usage and average rainfall.

4. **Actual vs Predicted Graphs:**

   - Scatter plots comparing predicted and actual yields for both models.

---

## Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/username/climate-crop-yield-predictions.git
   ```
2. Navigate to the repository:
   ```bash
   cd climate-crop-yield-predictions
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```
4. Execute cells step-by-step to explore the analysis.

---

## Results Summary

- **Insights:**
  - Temperature and rainfall strongly influence crop yields.
  - Pesticide usage emerges as a critical factor in improving yields.
- **Model Performance:**
  - Random Forest achieved an R² score of 0.99.
  - Random Forest performed better, highlighting its robustness in handling nonlinear data.

---
