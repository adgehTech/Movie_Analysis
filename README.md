# Data Analysis on Movies Data

### About the  Data

This analysis includes cleaning data, explanation about the data and answering questions listed at question part.

This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. There are some odd characters in the ‘cast’ column. 

### Questions

- Which genres are most popular from year to year?
- What kinds of properties are associated with movies that have high revenues?

### Findings

I traversed through data wrangling and exploratory data analysis in the given movie data and I take research to answer asked questions about movie genres, elements driving high revenues, and future projections regarding genre popularity. 
I used Bar charts, scatter, regration line, and correlation matrix to visuallize datas respectively.

Bar charts were used to visually represent the most popular genres for each year, revealing the changing tastes of moviegoers throughout time. To show the links between budget, popularity, runtime, and vote average in relation to income, scatter plots were used. And I used correlation matrix plot of the matplotlib to visualize properties Associated with High Revenues.
 
From this analiysis I found arrays of most popular genres from year to year and strong positive correlations between budget, popularity, and revenue were found by conducting more research on assets associated with large revenues.

### Technologies

```python
# It's a fundamental tool for data preprocessing and exploration.
import pandas as pd 

# It provides support for large, multi-dimensional arrays and matrices, along with mathematical functions to operate on these elements.
# Efficient numerical operations are crucial for data manipulation and scientific computing. 
import numpy as np

# It provides a wide variety of plots and charts to visualize data and is often used for creating static, interactive, and animated plots. 
import matplotlib.pyplot as plt

# It is a data visualization library based on Matplotlib, offering additional features and a high-level interface for creating attractive and informative statistical graphics.
import seaborn as sns

# It provides functionalities for creating and training machine learning models, including tools for evaluating model performance and selecting hyperparameters.
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.ensemble import RandomForestClassifier

# It is used for encoding categorical variables into numerical values, an essential step in preparing data for machine learning models.
from sklearn.preprocessing import LabelEncoder 
```

## 🌐 Contact me:
[![Portfolio](https://img.shields.io/badge/Portfolio-%232696F1.svg?style=for-the-badge&logo=webflow&logoColor=white)](https://belaybirhanu.netlify.app) 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/belay-birhanu) [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/adgehTech) [![Telegram](https://img.shields.io/badge/Telegram-%232CA5E0.svg?logo=telegram&logoColor=white)](https://t.me/adgehTech) 