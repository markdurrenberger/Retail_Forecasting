# Retail Sales Classification Model
This repo contains a capstone project from Springboard's Data Science Career Track certificate program. The project contains a machine learning classification model built on actual sales and customer data from a telecommunications retailer. The company and customer identifying information has been changed to protect company information.

## Business Case
This model was built to forecast customers moving their purchses "up market." The products sold by this retailer have a natural progression from entry-level (lower priced) products up to high-end (and higher priced) versions. A key business question for this retailer, therefore, is _how can we help accelerate customers moving their purchase behavior to higher priced items?_

## Methodology
To address this question, I took all of the sales data from the past five years and combined it with two other databases with customer specific data (such as industry, sales rep, length of customer relationship, etc.) to build a classification model to forecast whether or not a given customer purchase would be a higher priced product than any of that customer's prior purchases.

## In-Depth Explanation
For an in-depth walkthrough of the process for building this model - from business case through data wrangling and model tuning/comparison - see the Capstone_FinalReport file in this repo.

__Python Libraries Used -__ This project utilzied the following Python libraries:
* Pandas
* Numpy
* Seaborn (& Matplotlib)
* Sklearn

__Machine Learning Techniques Utilized:__
* Extensive Data Cleaning
* Joining multiple datasets
* Random Forest classifier
* Support Vector Machine classifier
* Feature Engineering
* Hyperparameter Tuning
* Model Comparison
* Non-technical explanation of results and findings/recommendations