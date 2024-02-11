# Aerofit-Customer-Insights 

**Project Overview**

This project leverages data analysis and visualization to uncover patterns in customer behavior for AeroFit treadmills. The goal is to identify key customer segments, understand purchasing preferences, and provide actionable recommendations to optimize marketing and product strategies.

**Problem Statement**

Aerofit seeks to refine its understanding of the diverse customer groups purchasing its treadmills. Using a dataset of past sales, this analysis aims to create customer profiles for distinct treadmill models and provide data-driven insights to guide targeted marketing and product development. 

**Dataset**

The dataset contains these features:

* **Product:** Treadmill model purchased.
* **Age:** Customer age.
* **Gender:** Customer gender. 
* **Education:**  Customer education level.
* **Marital Status:** If the customer is single or partnered.
* **Usage:** Estimated treadmill usage frequency (times per week).
* **Fitness:** Customer's self-assessed fitness level (scale of 1-5).
* **Income:**  Customer's annual income.
* **Miles:**  Average weekly mileage expected on the treadmill.

**Methodology**

1. **Data Preparation:** 
   * Load dataset using Pandas, verify data integrity, check for missing values.
   * Handle outliers with descriptive statistics and visualization.

2. **Exploratory Data Analysis (EDA):**
   * Calculate descriptive statistics (mean, median, distribution) for numerical features.
   * Visualizations using Matplotlib and Seaborn:
      * Distribution of purchases across treadmill models.
      * Relationships between product choice and demographics (age, gender, marital status, etc.).
      * Correlations between key variables.

3. **Probability Analysis:**
   * Marginal probabilities to assess overall product popularity.
   * Conditional probabilities to examine how factors like income, age, and gender  influence product choice.

4. **Customer Profiling:**
    * Develop distinct customer profiles for each treadmill model, highlighting the most relevant  features for each segment.

**Key Findings** 
* Customer Profiles Vary: Distinct customer profiles emerge for each treadmill model. The KP281 appeals primarily to younger (26), partnered individuals with mid-range income.  KP781 buyers tend to be slightly older (27), male,  have higher fitness levels, higher income, and plan on greater treadmill usage.

* Income Influences Product Choice:  A clear correlation exists between income level and treadmill model preference. Higher-income customers strongly favor the more expensive KP781,  while lower-income buyers lean towards the entry-level KP281.

* Data Skews: Several features in the dataset (age, income, miles)  exhibit right-skewed distributions. This indicates the presence of some higher values which might have been treated as outliers during analysis.


**Technologies Used:**

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

**Project Structure**

* `Aerofit_Business_Case - Shubham Yeole.ipynb`:  Jupyter Notebook with full analysis.
* `aerofit_treadmill.txt`: Raw dataset (if sharing)
* `README.md`: This file 

**Contact**

For further discussion of this project, please connect with me on LinkedIn or reach out at shubhamyeole565@gmail.com.


