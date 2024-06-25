# Insurance Forecasting and Customer Segmentation

## Overview
This project aims to assess financial risk associated with customers and categorise them into different risk segments for better-targeted product offerings. The project focuses on:
1. **Financial Risk Forecasting**:
   - Predicting the claim amount for non-zero claims.
   - Estimating the likelihood of a claim being filed.

2. **Customer Segmentation**:
   - Identifying the most profitable and least risky customer segments.
   - Classifying customers into segments based on their features.

## Data
The dataset (`insurance_data.csv`) includes information about customers, their vehicles, and their insurance details. Key columns include:
- `Car_id`: Unique identifier for each car.
- `Date`: Date of the record.
- `Customer Name`: Name of the customer.
- `Gender`: Gender of the customer.
- `Annual Income`: Annual income of the customer.
- `Dealer_Name`: Name of the car dealer.
- `Company`: Car company.
- `Model`: Car model.
- `Engine`: Type of engine.
- `Transmission`: Transmission type.
- `Color`: Car color.
- `Price ($)`: Price of the car.
- `Dealer_No`: Dealer number.
- `Body Style`: Body style of the car.
- `Phone`: Customer's phone number.
- `Amount_paid_for_insurance`: Amount paid for insurance.
- `Claim amount`: Amount claimed.
- `City`: City of the customer.

## Notebook
The Jupyter notebook (`Insurance_Forecasting.ipynb`) includes the following sections:
1. **Business Problem Definition**:
   - Financial Risk Forecasting
   - Customer Segmentation

2. **Data Science Problem Definition**:
   - Regression Model for claim amount prediction.
   - Probability Model for claim likelihood estimation.
   - Clustering Model for customer segmentation.
   - Classification Model for customer segment prediction.

3. **Data Understanding and Preparation**:
   - Loading and inspecting the dataset.
   - Handling missing values and data preprocessing.
