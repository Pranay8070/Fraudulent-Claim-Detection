# Fraudulent Insurance Claim Detection - Global Insure

## 📌 Problem Statement
Global Insure, a prominent insurance provider, handles thousands of claims each year. However, a notable share of these claims are fraudulent, leading to significant financial losses. The existing fraud detection method is manual, inefficient, and often identifies fraud too late—after claim settlement. The company aims to leverage data analytics to flag fraudulent claims early, improving accuracy, reducing losses, and streamlining the claims process.

---

## 🎯 Business Objective
The objective is to develop a predictive model that classifies insurance claims as **fraudulent** or **legitimate** using historical data. By analyzing features such as claim amount, customer details, and incident characteristics, the model will help the company proactively detect fraud before approval.

---

## ❓ Key Questions
- How can historical claim data be analyzed to uncover fraud patterns?
- Which features most strongly indicate fraudulent activity?
- Can we predict the fraud likelihood for a new claim?
- What model insights can improve fraud detection strategies?

---

## ✅ Tasks Overview
1. Data Preparation  
2. Data Cleaning  
3. Train-Validation Split (70-30)  
4. Exploratory Data Analysis (EDA) - Training Data  
5. EDA on Validation Data *(optional)*  
6. Feature Engineering  
7. Model Development  
8. Predictions and Evaluation  

---

## 📂 Data Dictionary
The dataset includes **1000 rows** and **40 columns**. Below are descriptions of key fields:

| Column Name                  | Description |
|-----------------------------|-------------|
| months_as_customer          | Duration in months the customer has held an insurance policy |
| age                         | Age of the insured individual |
| policy_number               | Unique identifier for each policy |
| policy_bind_date            | Date the policy was initiated |
| policy_state                | State where the policy applies |
| policy_csl                  | Combined single limit of the policy |
| policy_deductable           | Deductible amount payable by the insured |
| policy_annual_premium       | Annual cost of the policy |
| umbrella_limit              | Extra liability coverage beyond standard policy |
| insured_zip                 | Zip code of the insured |
| insured_sex                 | Gender of the insured |
| insured_education_level     | Education level of the insured |
| insured_occupation          | Occupation of the insured |
| insured_hobbies             | Listed hobbies of the insured |
| insured_relationship        | Relationship to the policyholder |
| capital-gains               | Profits from asset sales |
| capital-loss                | Losses from asset sales |
| incident_date               | Date of the incident or accident |
| incident_type               | Type/category of the incident |
| collision_type              | Type of vehicle collision involved |
| incident_severity           | Severity of the incident |
| authorities_contacted       | Authorities contacted post-incident |
| incident_state              | State where incident took place |
| incident_city               | City where incident occurred |
| incident_location           | Specific location of the incident |
| incident_hour_of_the_day   | Hour of the incident occurrence |
| number_of_vehicles_involved| Number of vehicles in the incident |
| property_damage             | Whether there was property damage |
| bodily_injuries             | Number of bodily injuries reported |
| witnesses                   | Number of witnesses at the scene |
| police_report_available     | Indicates if a police report exists |
| total_claim_amount          | Total amount claimed |
| injury_claim                | Amount claimed for injuries |
| property_claim              | Amount claimed for property damage |
| vehicle_claim               | Amount claimed for vehicle damage |
| auto_make                   | Car manufacturer |
| auto_model                  | Model of the vehicle |
| auto_year                   | Year of vehicle manufacture |
| fraud_reported              | Indicates whether the claim was fraudulent |
| _c39                        | Unknown/unlabeled variable |

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Machine Learning: Logistic Regression, Random Forest
- Evaluation Metrics: Accuracy, Recall, Precision, PR Curve

---

## 📊 Outcome
The developed model aims to assist Global Insure in identifying high-risk claims at an early stage, allowing for proactive fraud investigation, cost savings, and improved customer service.

---

> 📁 Feel free to fork, clone, or contribute to this project to help enhance fraud detection capabilities using machine learning.
