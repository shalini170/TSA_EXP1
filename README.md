# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 17/11/2025

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
 import pandas as pd
import matplotlib.pyplot as plt

# Example time series data
data = {
    'Date': pd.date_range(start='2023-01-01', periods=10, freq='D'),
    'Value': [10, 12, 9, 15, 18, 20, 17, 22, 25, 24]
}

# Create DataFrame
df = pd.DataFrame(data)

# Plot time series
plt.figure(figsize=(8,5))
plt.plot(df['Date'], df['Value'], marker='o', linestyle='-', color='blue')
plt.title('Time Series Plot')
plt.xlabel('Date')
plt.ylabel('Value')
plt.grid(True)
plt.show()
```

# OUTPUT:

<img width="1054" height="710" alt="image" src="https://github.com/user-attachments/assets/aea83a1a-9219-4097-9800-2abba0a7efb2" />

#result:
Thus we have created the python code for plotting the time series of given data



# RESULT:
Thus we have created the python code for plotting the time series of given data.
