# Customer Churn Analysis for PowerCo – BCG X Job Simulation

# Executive Summary
As part of the BCG X Data Science Virtual Job Simulation (April 2025), I conducted an end-to-end customer churn analysis for PowerCo, a major electricity and gas provider to small and medium-sized enterprises (SMEs). The analysis revealed a churn rate of 9.7% across 14,606 customers in the SME division. A predictive model using a Random Forest algorithm achieved 85% accuracy, successfully identifying customers at risk of churning. However, price sensitivity was not the main driver of churn. Instead, the key predictors were:

- Yearly consumption

- Forecasted consumption

- Net margin

The simulation also tested the effectiveness of a discount strategy. A 20% discount was found to be impactful only when targeted to high-value customers with a high probability of churn, offering a more cost-effective retention approach.

# Dataset
Find the dataset here:
<a href= "https://github.com/divyakadava61/Customer-Churn-Analysis/blob/main/client_data%20(1).csv"> Client Data <\a>
<a href = "https://github.com/divyakadava61/Customer-Churn-Analysis/blob/main/price_data%20(1).csv"> Price Data <\a>
# Goal
To investigate whether price sensitivity is the primary driver of customer churn at PowerCo and to develop a machine learning model that predicts churn with high accuracy. The project aimed to recommend data-backed strategies to reduce churn and retain high-value customers.

# Process
1. Business Understanding & Problem Definition

- Understood churn as a critical business issue for PowerCo.

- Formulated a hypothesis that price sensitivity could be a key factor influencing customer churn.

2. Data Integration & Cleaning

- Worked with three datasets: customer profiles, historical pricing, and churn indicators.

- Merged and structured the data using Pandas and NumPy in Python.

3. Exploratory Data Analysis (EDA)

- Performed statistical summaries, visualized distributions, and explored correlations.

- Identified key variables influencing customer behavior.

4. Feature Engineering

- Defined and calculated price sensitivity using principles of price elasticity.

- Engineered new features, including net margin, average consumption, and contract duration.

5. Model Building & Optimization

- Developed binary classification models including Logistic Regression, Gradient Boosting, and Random Forest, selecting the latter for its balance of accuracy and interpretability.

- Achieved 85% model accuracy in predicting churn outcomes.

6. Insights & Recommendations

- Price sensitivity was not among the top three drivers of churn.

- Customers with high yearly consumption, forecasted usage, and net margin were most likely to churn.

- A 20% discount strategy was validated through scenario testing, but only effective when offered selectively to high-value, high-risk customers.

7. Reporting

- Delivered a concise executive summary for stakeholders, including actionable recommendations based on data insights.

# Key Insights
Churn Rate: 9.7% of SME customers are churning.

Top Drivers: Yearly consumption, forecasted consumption, and net margin—not pricing—drive churn behavior.

Retention Strategy: Offering a blanket discount is inefficient; targeted retention campaigns focusing on high-value, high-risk customers are significantly more cost-effective.

# Conclusion
This project highlighted the value of data science in driving strategic decisions. Through predictive modeling, statistical analysis, and hypothesis testing, I was able to deliver clear business recommendations to reduce churn and optimize resource allocation. The work demonstrated not only technical proficiency in Python and machine learning but also the ability to translate data into high-impact business insights.
