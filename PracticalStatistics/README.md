# Project: Practical Statistics - Probability, A/B Testing, Regression 

## Project Details
This project utilizes Probability, A/B Testing, and Regression analysis to evaluate the impact of a new e-commerce webpage design on user conversions compared to an existing version. The aim is to ascertain whether the proposed changes yield a significant improvement in conversion rates and to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

Skills demonstrated in this project include:

* Proficiency in probability theory, A/B testing, and regression analysis  
* Formulating hypotheses and conducting hypothesis testing  
* Data wrangling and manipulation using Pandas  
* Statistical modeling and interpretation using statsmodels  
* Visualization of analysis results using Matplotlib  


## Analysis and Statistics

### **Q & A:**

1.  What is the probability of user conversion for each webpage design?
2.  Is there a significant difference in conversion rates between the new and old webpage designs?
3.  How does the probability of receiving the new webpage design compare to the old design?
4.  What are the null and alternative hypotheses for comparing conversion rates between the old and new webpage designs?
5.  How do we simulate samples to perform hypothesis testing for conversion rates?
6.  What proportion of the simulated sample differences in conversion rates is greater than the actual difference observed in the data?
7.  What are the z-score and p-value obtained from the regression analysis, and what do they signify regarding webpage conversion rates?
8.  How does the inclusion of additional factors, such as user country, impact conversion rate analysis?
9.  Is there a significant interaction between webpage type and user country regarding conversion rates?
10. Based on the analysis results, what recommendations can be made regarding the implementation of the new webpage design?

### Statistical and Analytical techniques used:

**Descriptive Statistics:**  
Calculating key metrics such as mean, median, and standard deviation to summarize conversion rates, page views, and user demographics.
Employing probability theory to analyze the likelihood of events occurring and to make informed predictions about user behavior.

**Probability:**  
Employing probability theory to analyze the likelihood of events occurring and to make informed predictions about user behavior.  

**A/B Testing:**  
Conducting A/B tests to compare the performance of different webpage designs and determine their impact on user conversions.

**Regression Analysis:**  
Performing regression analysis to investigate the relationship between variables and predict conversion outcomes based on factors such as webpage type and user demographics.

**Data Visualization:**  
Utilizing various visualizations including histograms, scatter plots, and box plots to graphically present the data and elucidate distributions and relationships between variables.
  

## Dataset 

**Main Dataset (ab_data.csv):**
* This dataset contains information about user interactions with the old and new webpage designs.  
* Key columns: user ID, timestamp, group (control or treatment), landing page type (old or new), and conversion status (converted or not).  
* It was used extensively for A/B testing, probability analysis, regression modeling, and hypothesis testing.  

**Additional Dataset (countries.csv):**
* This dataset includes information about the country of each user.
* It consists of user IDs and corresponding country codes.
* The dataset was merged with the main dataset to analyze the impact of user country on webpage conversion rates.
* Used in regression analysis to explore potential interactions between webpage type and user country.


## Software and Packages

Python  
NumPy  
Pandas  
Matplotlib   
StatsModels   
Jupyter Notebooks  
 
## Files

ab_data.csv  
countries.csv
