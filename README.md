# R_D_Infro_Technology - Data Visualization

Project- Customer Churn Analysis and Prediction

Project Overview:
This project analyzes customer churn in an e-commerce platform.
The goal is to predict which customers are likely to leave.
Helps businesses improve customer retention and increase revenue.
Objectives

Business Goals
Identify factors that lead to customer churn.
Provide insights to help businesses retain customers.
Suggest strategies to improve customer satisfaction.
Technical Goals

Clean and analyze customer data.
Train a machine learning model to predict churn.
Evaluate model performance using accuracy and other metrics.
Dataset Information

CustomerID – Unique ID for each customer.
Tenure – Number of months a customer has been active.
PreferredPaymentMode – Payment method used by the customer.
OrderCount – Total number of orders placed.
CouponUsed – Number of coupons applied.
WarehouseToHome – Distance from warehouse to home.
HourSpendOnApp – Time spent on the app daily.
SatisfactionScore – Rating from 1 to 5.
Complain – Whether the customer has raised a complaint (1 = Yes, 0 = No).
CashbackAmount – Total cashback received.
Churn – Target variable (1 = Churned, 0 = Active Customer).
Exploratory Data Analysis (EDA)

Analyzed churn patterns based on:
Marital Status
Satisfaction Score
Preferred Payment Mode
Order History
Cashback Usage
Used visualizations like bar charts and histograms.
Machine Learning Model

Used Random Forest Classifier for churn prediction.
Steps:
Data Cleaning and Preprocessing
Feature Selection
Train-Test Split
Model Training
Performance Evaluation
How to Run the Project

Clone the Repository

git clone https://github.com/your-repository-link.git

cd your-repository-folder

Install Dependencies

pip install pandas numpy matplotlib seaborn scikit-learn

Update the File Path

Modify this line in the script: df = pd.read_excel('E_Commerce_Dataset.xlsx')

If the file is in a folder: df = pd.read_excel('./data/E_Commerce_Dataset.xlsx')

Run the Jupyter Notebook or Script
If using Jupyter Notebook: jupyter notebook

If using a Python script: python churn_analysis.py

Results & Business Insights

Customers with low satisfaction scores churn more.
Frequent complaints are linked to higher churn rates.
Cashback programs improve customer retention.
Payment method choice has a small effect on churn.
Recommendations

Improve customer support for those who file complaints.
Offer loyalty rewards to reduce churn.
Personalize marketing based on churn risk.
Enhance user experience to boost retention.
Future Improvements

Fine-tune the model for better accuracy.
Analyze churn trends over time.
Use real-time customer data for live predictions.
Experiment with deep learning models.
License

This project is open-source under the MIT License.
Contact & Contributions

Open an issue or submit a pull request for improvements.
Connect on LinkedIn / GitHub for collaboration.
