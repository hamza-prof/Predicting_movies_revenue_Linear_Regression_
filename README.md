# Predicting Movies Revenue Using Linear Regression

This project involves predicting the revenue of movies based on various factors using a linear regression model built from scratch. The dataset used for this project is the IMDb Movies dataset. The project begins with exploratory data analysis (EDA) and then proceeds to build and evaluate a linear regression model.

## Project Overview

The goal of this project is to predict the revenue of movies based on multiple features such as budget, genre, and production details. The model is built from scratch using Python, utilizing libraries such as Pandas, Matplotlib, Seaborn, and Scikit-learn.

## Dataset

The dataset used in this project is the IMDb Movies dataset, which contains information about movies such as:

- Title
- Genre
- Budget
- Revenue
- Rating
- Director, and more

The dataset was cleaned and processed before being used to train the model.

## Steps Involved

1. **Exploratory Data Analysis (EDA)**:

   - Visualizing missing values.
   - Analyzing the correlation between features.
   - Visualizing distributions of numeric features.
   - Exploring word clouds for text data features.
   - Feature engineering and data cleaning.

2. **Linear Regression Model**:
   - Building the model from scratch using basic linear algebra.
   - Training the model using the processed dataset.
   - Evaluating the model’s performance using various metrics like Mean Squared Error (MSE).

## Libraries Used

The following Python libraries are used in this project:

```python
import datetime
import ast
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
from wordcloud import WordCloud, STOPWORDS
from sklearn.preprocessing import StandardScaler
```

- `pandas`: For data manipulation and analysis.
- `matplotlib` & `seaborn`: For data visualization.
- `numpy`: For numerical operations and calculations.
- `wordcloud`: For generating word clouds.
- `sklearn`: For preprocessing the data.

## Installation

To run this project, you need to have the following dependencies installed. You can install them using `pip`:

```bash
pip install pandas matplotlib seaborn numpy scikit-learn wordcloud
```

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/hamza-prof/Predicting_movies_revenue_Linear_Regression.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Predicting_movies_revenue_Linear_Regression
   ```

3. Run the Jupyter notebook or Python script to see the implementation of the EDA and the linear regression model.

## Key Features

- **Exploratory Data Analysis (EDA)**: Visualizations and summary statistics to better understand the dataset.
- **Linear Regression Model**: A model built from scratch, without using libraries like `LinearRegression` from `sklearn`, to predict the revenue of movies.
- **Word Cloud**: Visualize the most common words from the movie descriptions.

## Results

The model's performance can be evaluated based on the Mean Squared Error (MSE) and other metrics. The predictions generated by the model help to understand how budget, genre, and other factors contribute to the movie revenue.

## Conclusion

This project demonstrates the power of linear regression in predicting movie revenues based on various features from the IMDb dataset. By performing EDA, cleaning the data, and building a model from scratch, you can get a deeper understanding of both the data and the machine learning process.
