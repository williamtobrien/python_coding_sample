This is a repository for a Python code sample cleaning and analyzing the effect of state budget data on democracy in 2005.

# Required Packages
`import pandas as pd`
`import numpy as np`
`import matplotlib.pyplot as plt`
`import sklearn`
`import seaborn as sns`
`import statsmodels.api as sm`
`import statsmodels.formula.api as smf`
`from sklearn.model_selection import train_test_split, KFold, cross_val_score`
`from sklearn.ensemble import RandomForestRegressor`
`from sklearn.tree import DecisionTreeRegressor`
`from sklearn.metrics import mean_squared_error, r2_score`

# Required Data
For my code to execute properly, you must have the data folder in your working directory. The only additional step before you can begin running the code is to download the V-Dem data from [this link](https://v-dem.net/data/the-v-dem-dataset/country-year-v-dem-fullothers-v15/)].
Once you have done that, put the .csv file inside the downloaded folder into the data folder (which should be your working directory). From there, you can begin running the code.
