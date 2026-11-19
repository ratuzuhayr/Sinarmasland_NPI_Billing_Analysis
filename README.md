# NPI & IPL Billing Analysis

## Overview
An exploratory data analysis project to evaluate Non-Performing Invoices (NPI) and IPL (Environmental Management Fee) billing performance. The project aims to identify outstanding payment patterns, evaluate collection effectiveness, and uncover potential billing data quality issues to support data-driven business decisions.

## Objectives
- Analyze NPI trends and outstanding amounts.
- Identify unit and cluster segments contributing to outstanding invoices.
- Evaluate vacant unit contributions and unusual water usage.
- Assess collection action effectiveness and reminder frequency.
- Analyze payment methods and owner contact data quality.
- Develop actionable business recommendations.

## Key Findings
- Overall NPI rate reached **36.96%**, representing 298,426 invoices.
- Total outstanding amount reached approximately **Rp246.40 billion**.
- Vacant units recorded a higher NPI rate (**59.43%**) than occupied units (**29.80%**).
- 3,824 invoices contained negative water usage records.
- Surat recorded the highest collection response rate at **5.22%**.
- 109,328 outstanding invoices were associated with incomplete or unverified owner contact information.

## Stakeholders
- Collection Team
- Finance Team
- Asset Management Team
- Township Management

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Dataset
The project uses five datasets:
- `sml_clusters.csv`
- `sml_units.csv`
- `sml_ipl_billings.csv`
- `sml_collection_actions.csv`
- `sml_payment_disputes.csv`

## Repository Structure
```text
npi-ipl-billing-analysis/
├── data/
├── [PWD]_FINAL_Capstone_3.ipynb
└── README.md
```

## Business Recommendations
- Strengthen NPI monitoring and collection prioritization.
- Improve follow-up strategies for vacant units and high-risk invoices.
- Validate unusual water usage records.
- Evaluate and optimize collection channels.
- Standardize payment method categories.
- Improve owner contact completeness and verification.

## Conclusion
The analysis highlights opportunities to improve IPL collection performance, billing data quality, and operational monitoring through data-driven insights.
