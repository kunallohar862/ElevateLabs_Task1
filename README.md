# ElevateLabs_Task1

In this file I have worked on stock market data. This data consists of 4 indexes:
* SPX  
* DAX  
* FTSE  
* NIKKEI  

I arbitrarily created missing values by deleting some data points in Excel.  
To handle those missing values, I applied two methods:

### 1. Forward Fill and Backward Fill  
This is commonly used in time series data which has a large amount of entries.  
It fills missing values using the value just before (forward fill) or just after (backward fill) the missing point.

### 2. Mean  
Mean, mode, and median are also used to fill missing data points in a dataset.  
For this dataset, I used the **mean** because it's completely numerical data, making mean a simple and effective method.
