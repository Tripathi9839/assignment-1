import pandas as pd
import numpy as np

# Sample dataset
data = {'Lot Area': [8500, np.nan, 9600, 11250, np.nan, 9550]}
df = pd.DataFrame(data)

# Mean Imputation
df['Lot Area Mean'] = df['Lot Area'].fillna(df['Lot Area'].mean())

# Median Imputation
df['Lot Area Median'] = df['Lot Area'].fillna(df['Lot Area'].median())

# Mode Imputation
df['Lot Area Mode'] = df['Lot Area'].fillna(df['Lot Area'].mode()[0])

print(df)
