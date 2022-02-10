# <p align="center">House Rent Prediction</p>
<p align="center"> 
<a href="https://www.linkedin.com/in/roy-ashish">
<img alt="linkedin" src="https://img.shields.io/badge/-Ashish Roy-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/roy-ashish"></a>
<img src="https://img.shields.io/badge/Version-1.0.0-blue" />
<img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-yellow.svg" target="_blank" />
<img src="https://img.shields.io/badge/Python-100%25-yellow?style=flat&logo=python&logoColor=yellow" />
</p>

## Motivation

To help Landlords, Tenants and Investors accurately price rental apartment to create a transparent and easy to navigate rental market, and thereby improving the efficiency of their investment returns.

## Our Goal

<img src="https://github.com/royashishneu/House_Rent_Prediction/blob/main/goals.png">

## Installation

Use the package manager pip or homebrew to install any necessary packages for your environment if you are running on local machine.

```bash
pip install geopandas
```
OR
```bash
brew install geopandas
```
## Packages Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
sns.set();
%matplotlib inline
from shapely.geometry import Point
import geopandas as gpd
from geopandas import GeoDataFrame
import plotly.express as px
from sklearn.preprocessing import LabelEncoder
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeRegressor
from sklearn.ensemble import RandomForestRegressor
from sklearn.linear_model import LinearRegression
from sklearn.neighbors import KNeighborsClassifier
from sklearn.metrics import accuracy_score
```
## Models Used

<img src="https://github.com/royashishneu/House_Rent_Prediction/blob/main/models%20used.png">

## Accuracy

<img src="https://github.com/royashishneu/House_Rent_Prediction/blob/main/accuracy.png">

## How to Use

Download the dataset from <a href="https://www.dropbox.com/error">here</a><br>
Simply clone and run .ipynb file

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
