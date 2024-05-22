
# Haberman EDA Analysis

# Problem Statement
The Haberman dataset documents the survival of patients who had undergone surgery for breast cancer. The dataset includes patients' age, the year of surgery, the number of positive axillary nodes detected, and their survival status (survived 5 years or more, or less than 5 years). Our objectives for this exploratory data analysis (EDA) are:

To understand the distribution of patients' age, year of operation, and number of positive nodes.
To investigate the relationship between these features and the survival status of patients.
To identify any patterns or trends that could provide insights into factors affecting survival after surgery.

# Approach
We will use Python tools such as Pandas, NumPy, Seaborn, and Matplotlib for this analysis. The dataset contains the following columns:

age: Age of the patient at the time of surgery.
year: Year in which the patient underwent surgery.
nodes: Number of positive axillary lymph nodes detected.
survival: Survival status indicating if the patient survived 5 years or more (1) or less than 5 years (2) after the surgery.
Steps:

Data Loading and Cleaning

Load the dataset using Pandas.
Check for missing values and handle them if any.
Convert data types if necessary.
Exploratory Data Analysis (EDA)

Univariate Analysis: Analyze the distribution of individual features (age, year, nodes) using histograms and box plots.
Bivariate Analysis: Explore the relationship between features and survival status using box plots, scatter plots, and violin plots.
Multivariate Analysis: Use pair plots and correlation heatmaps to understand the interplay between multiple features and survival status.
Visualization

Use Seaborn and Matplotlib to create visualizations that highlight the key findings from the EDA.
Create plots such as histograms, box plots, scatter plots, violin plots, and pair plots.
Statistical Analysis

Calculate summary statistics (mean, median, standard deviation) for the features.
Perform hypothesis testing to determine if observed differences between survival groups are statistically significant.

# Conclusion
The EDA provides the following insights:

Age Distribution:

The age of patients at the time of surgery ranges broadly, with most patients between 30 and 80 years old. The median age is around 52 years.
The age distribution shows no significant difference between the survival groups, suggesting age alone may not be a decisive factor in predicting survival.
Year of Surgery:

The surgeries occurred between 1958 and 1969, with a relatively uniform distribution across these years.
No clear trend or significant difference in survival rates based on the year of surgery is observed.
Positive Axillary Nodes:

The number of positive nodes ranges from 0 to more than 30, but most patients have fewer than 5 positive nodes.
There is a noticeable difference in the number of positive nodes between the two survival groups. Patients who survived less than 5 years generally had more positive nodes, indicating a possible correlation between a higher number of positive nodes and lower survival rates.
Survival Analysis:

Patients with fewer positive nodes tend to have higher survival rates. This is visualized through box plots and scatter plots showing the distribution of nodes across survival statuses.
The survival status shows that a higher number of nodes correlates with a lower chance of surviving 5 years or more post-surgery.
Statistical Tests:

Conduct t-tests or non-parametric tests (like the Mann-Whitney U test) to confirm if the differences in the number of positive nodes between survival groups are statistically significant.
These insights suggest that while age and year of surgery do not significantly impact survival, the number of positive axillary nodes is a critical factor. This information can guide further medical research and improve treatment planning for breast cancer patients, potentially leading to better survival outcomes
