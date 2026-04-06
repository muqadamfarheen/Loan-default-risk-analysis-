# Loan-default-risk-analysis
### PROBLEM STATEMENT 
Horizon Financial Group has experienced a significant increase in loan defaults across its personal lending portfolio during 2024–2025. With over 600 loans issued, the current default rate stands at approximately 25%, which is more than double the company’s target default rate of 12%. This rising trend poses a substantial risk to profitability, portfolio stability, and overall risk management practices.
The objective of this analysis is to identify the key factors contributing to loan defaults by examining borrower characteristics (such as demographics, income, employment status, and credit score) alongside loan attributes (including loan amount, tenure, and interest rate). By leveraging these datasets, the analysis aims to uncover patterns, correlations, and high-risk segments within the loan portfolio.
The insights derived from this study will support the VP of Risk in refining the company’s credit scoring model, improving underwriting criteria, and establishing more effective loan approval thresholds to reduce future default rates and enhance portfolio performance.

# ANALYSIS REPORT

### Executive Summary
This report presents a comprehensive analysis of loan default risk using borrower demographics, credit profiles, and loan characteristics. The primary objective is to identify key risk factors influencing defaults, evaluate borrower behavior, and recommend strategies to minimize financial losses. Key findings highlight strong correlations between credit score, income levels, and default probability, along with actionable insights for improving credit risk assessment.

### Data Collection
The data used for this analysis was collected from multiple internal and external sources:
Borrower Profile: Demographics, income, credit score and employment etc
Loan Attributes: Amount, term , interest rate, repayment status,etc 

### Methodology
The dataset was cleaned, processed, and analyzed using tools such as Excel, Python, and SQL. The following techniques were applied:
Data Cleaning: handled null values, duplicate values , inconsistent values 
Feature Engineering: Credit Buckets , DTI Buckets, Employment 
Exploratory Data Analysis (EDA): To understand distributions and detect anomalies
Segmentation Analysis: Borrowers grouped by credit score, income, and loan type

### Data Analysis
Key metrics analyzed include:
Default Rate: Overall default rate stood at 24% across the portfolio
Credit Score Impact: Borrowers with scores below 600 had a higher default rate
Income Levels: Low-income borrowers showed a significantly higher likelihood of default
Loan Amount: Higher loan amounts were moderately associated with increased risk

### Findings and Insights
The analysis revealed several important insights:
High-Risk Segments:
-Borrowers with less than 600 credit score were most likely to default.




-Borrowers with high debt to income ratio were most likely to default .










-Borrowers with short employment i.e less than 2 years employment history were most likely to default on a loan









-The top three loan categories with the highest default rates are wedding loans, home improvement loans, and auto loans.
















Key Risk Drivers:
Credit score, income level, and employment history were the strongest predictors
Moderate Risk Factors:
High loan amounts contributed to increased risk but were less impactful than credit history










### Recommendations
Based on the findings, the following actions are recommended:
Minimum credit score requirement set at 600 to ensure baseline creditworthiness.
Maximum Debt-to-Income (DTI) ratio capped at 40% to maintain manageable borrower leverage
Applicants must have a minimum of 2 years of stable employment to demonstrate income consistency.
Conduct enhanced verification for loans related to wedding, home improvement and auto purposes to ensure lower default risk.
Implement stricter due diligence for high-value loan amounts including additional income and repayment capacity checks

### Conclusion
This loan default risk analysis provides valuable insights into borrower behavior and key factors influencing defaults. By leveraging data-driven strategies and implementing targeted risk management practices, financial institutions can reduce default rates, improve portfolio quality, and enhance overall profitability.

