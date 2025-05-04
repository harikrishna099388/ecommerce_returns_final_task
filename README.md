# ecommerce_returns_final_task
# E-commerce Return Rate Reduction Analysis
# Objective
As someone exploring ways to reduce product returns in online shopping, I wanted to understand why customers send items back and which products are most at risk. This project uses Python and Power BI to do just that — clean the data, train a model, and visualize the risk areas clearly
# Dataset
The data used here is a synthetic e-commerce dataset of 10,000 orders with fields like:
 Product details (category, price, quantity)
 User demographics (age, gender, location)
 Return behavior and reasons
 Payment and shipping info
# Tools I Used
 **Python in Google Colab** – For cleaning, feature engineering, and modeling
 **scikit-learn** – To build a logistic regression model that predicts return probability
 **Power BI** – For an interactive dashboard with filters and drill-through analysis
# Steps I Followed
1. Cleaned and processed the dataset (filled missing values, created new features like `days_to_return`).
2. Encoded categorical variables to numeric format.
3. Trained a logistic regression model using scikit-learn.
4. Predicted return probability for each product.
5. Filtered products with return risk > 70%.
6. Exported CSVs for Power BI analysis.
# Dashboard Insights
 Returns by category and user location
 Risk scores visualized by shipping/payment methods
 Filters for better drill-down: category, gender, region, etc.
# How to Run It
1. Open the `.ipynb` file in Google Colab.
2. Upload the dataset when prompted.
3. Run all cells to generate return predictions.
4. Download the output files.
5. Import `return_analysis_dataset.csv` into Power BI and build visuals.
