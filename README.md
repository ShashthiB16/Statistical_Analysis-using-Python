# **Statistical Analysis of Petrol Consumption Dataset using Python**

# **Project Objectives**

* Analyze the statistical properties of the dataset.
* Calculate measures of central tendency (Mean, Median, Mode).
* Study data distribution using skewness.
* Detect outliers using the IQR method.
* Visualize data using different statistical plots.

# **Dataset Information**

Dataset Name: Petrol_Consumption.csv

Features:

* Petrol_tax
* Average_income
* Paved_Highways
* Population_Driver_licence
* Petrol_Consumption

# **Technologies Used**

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn

# **Project Workflow**

Step 1: Import Libraries

import numpy as np

import pandas as pd

import seaborn as sb

import matplotlib.pyplot as plt

Step 2: Load Dataset
df = pd.read_csv("Petrol_Consumption.csv")

Step 3: Data Preprocessing
* Rename columns
* Check data types
* Explore dataset information

Step 4: Statistical Analysis
* Mean
* Median
* Mode
* Skewness

Step 5: Outlier Detection
* Calculate Q1 and Q3
* Find IQR
* Detect outliers

Step 6: Visualization
* KDE plots
* Boxplots
* Distribution analysis

# **Key Insights**

 **Central Tendencies:**
 
The average petrol tax was 7.67, average income was 4241.83, average paved highways were 5565.42, average driver licence percentage was 0.570,
and average petrol consumption was 576.77. The median petrol consumption was 568.50, indicating that the data is reasonably centered around the average values.

**Outlier Analysis:** 

Outliers were detected in multiple variables. Paved Highways contained extreme values at indices 5 and 36, Average Income had an outlier at index 11,
Petrol Consumption had an outlier at index 18, and Population Driver Licence contained outliers at indices 6 and 39. Removing these outliers improved the consistency
of the dataset.

**Variability Measures:** 

The standard deviation of Petrol Consumption was 80.64, indicating moderate variation in consumption across regions. T
he variance of petrol consumption was 6502.24, while paved highways showed the highest variance (6,775,117), suggesting a large difference in road infrastructure
among states.

**Correlation Analysis:** 

Petrol consumption had a negative correlation with petrol tax (-0.463) and average income (-0.254), while it showed a positive correlation with paved highways (0.215)
and population driver licence percentage (0.698). This suggests that higher driver licence percentages are strongly associated with increased petrol consumption.

**Confidence Interval Results:**

* **Smartphone Screen Time (90% CI):**
The true mean screen-on time lies between **9.99 and 10.17 hours**.

* **Delivery Time (95% CI):**
The true average delivery time lies between **29.35 and 30.55 minutes**.

* **Student Study Hours (99% CI):**
The true average weekly study hours lie between **14.78 and 16.16 hours**.

**Hypothesis Testing Results:**

For both AutoDrive Components Ltd. and FreshBake Foods Pvt. Ltd., the hypothesis tests resulted in accepting the null hypothesis (H₀). 
This indicates that there is insufficient statistical evidence to conclude that the actual assembly time or baking time has increased beyond the values
predicted by the theoretical models.

# **Conclusion**

The statistical analysis revealed meaningful patterns in the dataset, including variations in petrol consumption, infrastructure differences, 
and relationships between variables. The confidence interval analysis provided reliable estimates of population means, while hypothesis testing showed no 
significant deviation from the theoretical business models. 

Overall, the project demonstrates the practical application of descriptive statistics and inferential statistics in solving real-world analytical problems 
and supporting data-driven decision-making.

