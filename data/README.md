# Dataset Description: Climate and Crop Yield Data

## Overview

This dataset is a comprehensive collection of climate and agricultural data aimed at supporting research in crop yield prediction. It contains information on climatic factors such as temperature, rainfall, and pesticide usage, alongside crop yield data from various regions over several decades. The dataset is intended for machine learning, statistical analysis, and data visualization applications to enhance agricultural decision-making.

---

## Contents

The dataset includes the following attributes:

- **Area**: The geographical region where data was collected (e.g., Albania, Algeria).
- **Item**: Type of crop (e.g., Maize, Potatoes, Rice).
- **Year**: Year of observation, ranging from 1990 to 2013.
- **hg/ha\_yield**: Crop yield measured in hectograms per hectare.
- **average\_rain\_fall\_mm\_per\_year**: Average rainfall in millimeters for the year.
- **pesticides\_tonnes**: Amount of pesticides used (in tonnes).
- **avg\_temp**: Average temperature for the region in degrees Celsius.

---

## File Details

- **File Name**: yield\_df.csv
- **File Size**: 1.49 MB
- **Format**: CSV (Comma-Separated Values)
- **Encoding**: UTF-8

---

## Data Source

The dataset was sourced from Kaggle - Crop Yield Prediction Dataset. It has been preprocessed to ensure consistency and usability for machine learning applications.


---

## Usage

To use the dataset:

1. Load the CSV file in Python using pandas:
   ```python
   import pandas as pd
   df = pd.read_csv('dataset.csv')
   ```
2. Explore the dataset:
   ```python
   print(df.head())
   print(df.info())
   ```
3. Perform cleaning or preprocessing steps if necessary:
   ```python
   df = df.dropna()  # Example: Drop rows with missing values
   ```

---

## Key Insights

This dataset provides rich information for:

- **Exploratory Data Analysis (EDA):** Analyze relationships between climatic variables and crop yields.
- **Feature Engineering:** Identify key factors influencing agricultural productivity.
- **Machine Learning Models:** Train predictive models for crop yield forecasting.

---

## Data Integrity

### Missing Values

- All missing values have been handled through imputation or removal.

### Duplicates

- The dataset has been checked for and cleaned of duplicate entries.

### Units

- **Rainfall**: Millimeters (mm)
- **Pesticides**: Tonnes (t)
- **Temperature**: Degrees Celsius (°C)
- **Yield**: Hectograms per hectare (hg/ha)

---

## Limitations

- **Temporal Granularity**: Yearly averages are provided; monthly or daily data is not included.
- **Geographical Bias**: Data availability may vary across regions.

---

##

