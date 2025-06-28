# **Implementation of Machine Learning in Credit Risk Analysis: Predicting Potential Customer Defaults**



This repository contains a comprehensive data science project developed as part of my final project internship at ID/X Partners. The project aims to predict potential loan default risk by leveraging historical Lending Club data from 2007 to 2014. 

The project is designed with CRISP-DM methodology, covering data analysis, feature engineering, dataset exploration, data preparation, predictive modeling, model evaluation, and business insight-based recommendations.

The dataset used includes 466,284 loan records with 75 variables describing the borrower profile, loan amount, repayment status, and credit history. The main objective of classification is the loan_status feature, which has been simplified into two classes:
- `GOOD`: Loans have been repaid
- `BAD`: Loans in collection, late payment, default, or have other default statuses

Given the highly skewed data distribution (the number of GOOD categories is much larger than BAD), the modeling and evaluation process is carefully designed to ensure the model's ability to detect risk effectively.


## 🎯 Background of the Problem

1. **Credit risk** is a **crucial element** that needs to be understood by financial institutions and loan service providers. To optimize the management of this risk, finance companies continue to strive to **improve creditworthiness assessment methods**. Approving loans to borrowers with a high risk of default can have a negative impact on the company's financial performance, and errors in transmitting credit risk have the potential to have serious consequences.

2. In the world of finance, a suboptimal credit granting process and inappropriate credit risk management can result in major losses. By applying **machine learning algorithms** to analyze large amounts of historical data, financial institutions can **uncover patterns and trends** that are difficult for human analysts to detect. This allows for **more accurate** credit decision making and **more efficient risk management**, thereby **minimizing potential losses** due to inappropriate credit granting.

3. Therefore, the development of a machine learning model that is able to predict potential defaults based on factors such as the customer's economic and financial conditions is very important to **avoid losses due to bad debts**.
## 🧠 Business Problem
1. How to **identify the risk of customer** default through historical data analysis to **improve the accuracy of credit** assessment by companies, so that companies can make more informed lending decisions?

2. **11% of 460k** customers still in default


## ❓ Problem Statement

How to **build a prediction model** that can **classify loan risk based on historical data**, so that companies can **reduce the potential for non-performing loans**?

## 📊 Business Impact & Recommendations

This model supports the data-driven credit scoring process by identifying high-risk applicants before loans are approved. This approach has the potential to reduce financial losses and improve the quality of the loan portfolio. Some future developments that can be done include:
- Incorporating data from external credit scoring agencies
- Balancing data distribution using methods such as SMOTE
- Regularly updating the model, for example every three months
- Implementing the model into the system via API or scoring dashboard
## 🧰 Tools Used
- Python: 3.9.12
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`,`scipy`,`sklearn`

## 💾 Source:
1. <a href="https://rakamin-lms.s3.ap-southeast-1.amazonaws.com/vix-assets/idx-partners/loan_data_2007_2014.csv">Loan Dataset</a>
2. <a href="https://docs.google.com/spreadsheets/d/1iT1JNOBwU4l616_rnJpo0iny7blZvNBs/edit?usp=sharing&ouid=106453318899954059421&rtpof=true&sd=true">Data Dictionary</a>

## 📁 File
1. `creditriskanalysis.py`
2. `CreditRiskAnalysis.ipynb`

## 📝 How to Use
1. Clone the repository or download `.ipynb` or `.py` file
2. Open the `.ipynb` file using [Google Colab](https://colab.research.google.com/) or Visual Studio Code (`.py` file)
   
```bash
git clone https://github.com/novanrw1611/credit-risk-analysis.git
