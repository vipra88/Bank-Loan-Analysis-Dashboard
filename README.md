
# Bank Loan Report
# Overview
The Bank Loan Report Project combines SQL for data manipulation and Tableau for visualization to create a comprehensive report on bank loan data. This report aims to provide stakeholders with actionable insights into loan applications, approvals, and related metrics.
# Data Source
The loan data for this project is sourced from an internal banking database, capturing comprehensive information about the bank's lending activities data source.
# Tools
* SQL: The project leverages SQL queries to retrieve, process, and analyze data database.
* PowerBI : Dynamic and interactive visualizations are crafted in PowerBI to present key findings effectively.
# Dashboards
## Dashboard 1: Summary
![sum](https://github.com/vipra88/Bank-Loan-Analysis-Dashboard/assets/144676864/3803bb17-f2b5-41e6-ab6f-8ae05b669c0f)
The Summary Dashboard captures key loan-related metrics and their changes over time, providing a snapshot of the loan portfolio's health and lending strategy impact. It includes the following KPIs:

* Total Loan Applications (MTD and MoM)
* Total Funded Amount (MTD and MoM)
* Total Amount Received (MTD and MoM)
* Average Interest Rate (MTD and MoM)
* Average Debt-to-Income Ratio (DTI) (MTD and MoM)

Additionally, it distinguishes between 'Good Loans' and 'Bad Loans,' with specific indicators for each category, helping in the assessment of loan portfolio quality.

### Dashboard 2: Overview
![Screenshot 2024-06-25 211552](https://github.com/vipra88/Bank-Loan-Analysis-Dashboard/assets/144676864/8ad574d6-5d61-43eb-9160-62ed87fff5a1)
The Overview Dashboard visually represents various loan-related metrics through different chart types:
- Monthly Trends by Issue Date 
- Regional Analysis by State 
- Loan Term Analysis 
- Employment Length Analysis 
- Loan Purpose Breakdown
- Home Ownership Analysis 

These visualizations aid in identifying trends, seasonal patterns, and the distribution of loans across various categories.

### Dashboard 3: Details

![Screenshot 2024-06-25 185438](https://github.com/vipra88/Bank-Loan-Analysis-Dashboard/assets/144676864/b08c4dd3-4eea-48b0-a7a1-bce21536c483)


The Details Dashboard offers a detailed view of the loan data, providing a comprehensive and user-friendly interface for accessing vital loan metrics, borrower profiles, and performance data.

#### Data Fields and Usage
The data utilized in the dashboards comprise several fields, each serving a specific purpose in loan management and risk assessment:

- Loan ID: Unique identifier for loans.
- Address State: Borrower location for regional analysis.
- Employment Length: Indicates - employment stability.
- Employee Title: Job title for income source verification.
- Grade/Sub Grade: Creditworthiness and risk classification.
- Home Ownership: Housing status for financial stability assessment.
- Issue Date: Loan origination date.
- Loan Status: Current state of the loan for performance tracking.
- Purpose: Loan reason for segmentation and customization.
- Term: Loan duration.
- Verification Status: Status of financial information verification.
- Annual Income: Yearly earnings for creditworthiness.
- DTI: Debt burden relative to income.
- Instalment: Monthly repayment amount.
- Interest Rate: Cost of borrowing.
- Loan Amount: Principal amount borrowed.

Each field plays a crucial role in managing loans, assessing borrower risk, structuring loan terms, and making informed lending decisions.

## Implementation
The project required importing the dataset from Excel into SQL Server for analysis and visualization using PowerBI. Dashboards were crafted using PowerBI powerful visualization tools and analytical capabilities, aligning with the specified requirements in the problem statement and utilizing the data dictionary to ensure precise field utilization.

## Data Validation
To ensure the accuracy and integrity of the data reflected in the dashboards, a thorough data validation process was undertaken. After the dataset was loaded into PowerBI and from SQL Server database, the following measures were implemented:
- SQL Query Verification: Direct queries were executed against the SQL Server database to retrieve raw data. This dataset served as a benchmark, validating the accuracy and consistency of the information presented in the dashboards.

- Data Consistency Checks: The results from PowerBI were compared against the SQL query results to ensure consistency. This step was critical to confirm that the data transformation and logic applied within Tableau did not alter the actual figures.

- KPI Logic Validation: The calculations and logic underlying the Key Performance Indicators (KPIs) were thoroughly reviewed. SQL scripts were employed to independently replicate the KPI calculations, ensuring the accuracy and reliability of the computations performed in PowerBI.


- Cross-Verification with Source Data: The transformed data in PowerBI was cross-verified with the source data from the SQL Server database. This step was crucial to confirm that all data transformations, including filtering, grouping, and aggregation, were correctly applied.


Through these validation steps, the project ensured that the PowerBI dashboards accurately represent the data, and the insights derived are based on truthful and unaltered information. This rigorous validation process enhances the credibility of the dashboards and reinforces confidence in the data-driven decisions made using these tools.

## Conclusion
By incorporating robust data validation techniques, the Bank Loan Dashboard project establishes itself as a reliable and authoritative source for monitoring the bank’s loan activities. The project not only presents critical data through intuitive visualizations but also guarantees the precision of the information displayed, enabling the bank to make informed and assured strategic decisions with confidence.



