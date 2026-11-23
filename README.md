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

<img width="1752" height="651" alt="image" src="https://github.com/user-attachments/assets/9079dc96-aa2e-4687-97b6-b7c9538bc56b" />
<img width="1753" height="575" alt="image" src="https://github.com/user-attachments/assets/b44c3aba-a1f0-4391-acca-2c9ad118e117" />
<img width="1750" height="815" alt="image" src="https://github.com/user-attachments/assets/9b55e8db-7dfe-4f03-8e34-32f335108c84" />
<img width="1755" height="657" alt="image" src="https://github.com/user-attachments/assets/64799274-dd56-4d18-a4ba-e338ca0f8ada" />
<img width="1760" height="811" alt="image" src="https://github.com/user-attachments/assets/6536c7d8-5250-4c8a-9206-b75dd4e6a05e" />
<img width="1750" height="802" alt="image" src="https://github.com/user-attachments/assets/f0ed0d65-bdfb-4a64-a5d1-08d25bd01f22" />
<img width="1751" height="550" alt="image" src="https://github.com/user-attachments/assets/e6ec2c12-44d6-48ab-a7ee-a02ed92c3ad7" />
<img width="1751" height="457" alt="image" src="https://github.com/user-attachments/assets/ffcf0b09-e7a1-4434-b1f9-b291ab8669bd" />
<img width="1756" height="536" alt="image" src="https://github.com/user-attachments/assets/03b4ff13-3535-4de1-9c99-23643a4fec7f" />
<img width="1756" height="552" alt="image" src="https://github.com/user-attachments/assets/ee8bb166-f258-4f92-aa25-8ee054fe3c63" />
<img width="1753" height="801" alt="image" src="https://github.com/user-attachments/assets/8913f096-a691-4641-99e3-51b5efa10192" />
<img width="1751" height="746" alt="image" src="https://github.com/user-attachments/assets/51cd7430-9417-4198-a3e6-11517686f1b2" />
<img width="1771" height="527" alt="image" src="https://github.com/user-attachments/assets/3ff0f96f-f38c-40c5-ad7b-d6ce24667bc2" />
<img width="1767" height="831" alt="image" src="https://github.com/user-attachments/assets/5ccef060-ee5f-49f1-b7d0-cdabddc2004f" />
<img width="1768" height="207" alt="image" src="https://github.com/user-attachments/assets/d9dd3443-6fa9-4e67-8531-e7c56af03ce5" />
<img width="1758" height="792" alt="image" src="https://github.com/user-attachments/assets/c8927a6a-6373-470e-a3c5-ee7d148b3260" />

# Summary of Work Performed

In this experiment, the Titanic dataset was loaded into Python using Pandas and analyzed using NumPy, Seaborn, and Matplotlib. The dataset was examined using functions such as head(), tail(), info(), describe(), shape, and nunique() to understand its structure, data types, statistical properties, and unique values.

Missing values were identified using isnull().sum() and handled using median imputation for the Age column, mode imputation for the Embarked column, and replacing missing Cabin values with "Unknown".

Outliers in the Age column were detected using boxplots and removed using the Interquartile Range (IQR) method. Data visualization techniques such as countplots and distribution plots were used to analyze passenger survival and age distribution. Cross-tabulation was performed to study the relationship between gender and survival, while a correlation heatmap was used to visualize relationships among numerical variables.

Techniques Used
- Data inspection and statistical analysis
- Missing-value handling
- Outlier detection using boxplots
- Outlier removal using IQR
- Countplot for categorical data
- Distribution plot (Displot)
- Cross-tabulation
- Correlation heatmap


# RESULT
 Thus we have read and performed Exploratory Data Analysis on the given data set.
