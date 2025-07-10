# 🛒 Walmart Null Value Handling - Full Project Journal

# <b> <font color= #ABFF00> Handling Null Values in Different Columns

### <b><font color= #FFFF00> Objective :

#### *This is a realistic Walmart sales dataset. In this project, I aim to handle the missing (null) values using practical, real-world logic based on the type and context of each column.*
### Part 1:
- #### *Import the necessary libraries and dataset, then analyze the structure and quality of the data.*
### Part 2:
- #### *Apply appropriate real-world logic to impute.*
### Part 3:
- #### *Plot the chart before and after handling null values, Final summary.*

# <b> <font color= #ABFF00> PART - 1

### <b><font color= #FFFF00> Import the librarys and Dataset :

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

```python
df = pd.read_csv(r"D:\B_Data_Anlysist_Project\Python_Projects\01_Handling_Null_Value\walmart_sales_with_nulls_value_dataset.csv")
df.head()
```

```python
df.shape
```

```python
df.info()
```

```python
df.isnull().sum()
