# Data-Analysis-with-Python
# Data Analysis Projects

Welcome to my repository! This project showcases my work and learning in data analysis, focusing on practical applications and insights drawn from various datasets. Below you'll find an overview of the techniques and analyses I've implemented.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Wrangling](#data-wrangling)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Visualizations](#visualizations)
- [Correlation Analysis](#correlation-analysis)
- [Contributing](#contributing)

## Project Overview

This project primarily revolves around analyzing sales data to derive meaningful insights regarding customer behavior and sales performance.

## Data Wrangling

- **Data Cleaning**: Handled missing values and inconsistent data types.
- **Feature Engineering**: Created new columns, such as `Calculated_Date`, using existing columns like `Year`, `Month`, and `Day`.

### Example Code

```python
import pandas as pd
```

# Load the data
```python
sales = pd.read_csv('sales_data.csv')
```

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) is performed to summarize the main characteristics of the dataset and uncover patterns.

- Descriptive Statistics: Calculated means, medians, and other statistical measures.
- Sales Trends: Analyzed sales trends by year and customer demographics.

Sample codes 
  ```python
  float(sales['Customer_Age'].mean())
 ```

  ```python
  sales['Year'].value_counts()
  ```

  ```python
  cond = sales['Revenue'] > 10_000

  float (sales.loc[cond, 'Order_Quantity'].mean())
  ```

