# EXNO2DS
# AIM:
      To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
dt=pd.read_csv("/content/titanic_dataset.csv")
dt
```
![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/ee434eec-8cac-433f-a51c-9b45bdff528b)

dt.info()
![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/eb2b57ad-abf9-496b-9612-fdf0221262df)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/624af37b-c7a6-41c7-b2e6-42485fb2699e)

dt.nunique()
![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/70cfcf57-780a-4980-9dee-a3495ded7b8d)

dt["Survived"].value_counts()
dt
![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/8c944151-eac5-4b3e-a219-b712630ec57e)


![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/45fc4d76-b744-4250-b136-f36a67e68c64)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/9ce34a94-0cc2-4657-9631-118033a151c4)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/9ce84e79-8271-47de-844e-e177794b40c3)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/27d80b2a-ccbd-4bc4-98d2-df8079ba594b)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/5d6464da-c732-452e-90a6-342011d02e7e)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/ef52840c-95d9-40ed-a421-12bab4ea7f23)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/52c8d65a-69cd-4a80-84c1-5eb91e380dc4)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/1cefe244-8d22-4c29-892c-4038f47455af)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/3f07d800-a4e6-4245-87fe-a6fab8d95a79)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/981fe443-5598-4641-a0e7-6c646615e265)

![image](https://github.com/vinodhini-17/EXNO2DS/assets/145742741/2a2aeee0-c380-4e57-8fe0-262cc051a3c2)

# RESULT

To perform Exploratory Data Analysis on the given data set executed successfully
      
