
## Brief project description
This project looks at three different csv files containing necessary information for billing for a hospital. The data source is from "code," "header," and "line," files that contain information such as ICD-10 code associated with each claim, claim number, procedure completed, cost of the claim, payer name, etc. This ensures that all encounters are accurately documented for proper payment to the hospitals. 

## Summary of key findings
1. Dominance of Medicare: Medicare is the top primary payer, making up for 62% of claims and the highest total charges ($131,008), indicating its significant financial impact on the healthcare services analyzed. 
2. High-Cost Diagnosis (J96.01): The ICD-10 code J96.01 (Acute respiratory failure with hypoxia) consistently appears as both a frequently occurring diagnosis and the diagnosis with the highest total charges ($$131,008), indicating its significant financial impact on the healthcare services analyzed. 
3. Primary Service Location: A significant majority of services (60%) took place in inpatient hospitals, highlighting that a substantial portion of the claims are related to hospital-based care

## Required libraries
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0