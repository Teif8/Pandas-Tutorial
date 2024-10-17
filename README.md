# Pandas-Tutorial
# Pandas Tutorial in Python

This repository provides a comprehensive guide for data analysis using the `pandas` library in Python. You'll learn how to load, manipulate, and inspect datasets using pandas.

## Getting Started
1. Clone the repository.
2. Install the required libraries by running: 
```
pip install -r requirements.txt
```
3. Open the Jupyter notebook: `pandas_tutorial.ipynb` and follow along with the examples.

## Dataset
The dataset used in this tutorial is `diabetes.csv`, which contains medical data on diabetes patients. It includes features like glucose levels, blood pressure, BMI, age, and the target variable (Outcome) indicating whether the patient has diabetes.

## Code Examples
- Importing pandas: 
```python
import pandas as pd
```

 Loading data from CSV:
```
diabetes_df = pd.read_csv('data/diabetes.csv')
```

 pandas_tutorial.ipynb:
The content in this file will be your Jupyter notebook (which you’ve shown in the image) and include the following sections:
	•	Import pandas
	•	Load data from diabetes.csv
	•	Inspect the DataFrame (e.g., .shape, .head())
	3.	data/diabetes.csv:
	•	Include the diabetes.csv file that you used for analysis in the /data folder.
	4.	requirements.txt:
- pandas
- numpy
