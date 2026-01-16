# Customer-Behaviour-Analysis-

About This Dataset
This is a comprehensive Customer Engagement and Churn Analytics Dataset containing behavioral, demographic, and transactional data for 50,000 customers across a global e-commerce/subscription platform. The dataset captures 25 distinct features that provide a 360-degree view of customer interactions and engagement patterns.

Dataset Characteristics
Records: 50,000 customers
Features: 25 columns
Data Types: Mixed (numerical, categorical, object)
Geographic Coverage: Multiple countries (USA, UK, Germany, Canada, India, Japan, France, Australia)
Time Period: Captures customer journey from signup through current status

# Architecture  
customer-behavior-analysis/
│
├── README.md
│
├── data/
│   ├── raw/                # NEVER TOUCHED
│   │   └── customers_raw.csv
│   │
│   ├── interim/            # after cleaning
│   │   └── customers_clean.csv
│   │
│   └── processed/          # model / BI ready
│       └── customers_features.csv
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_eda_visualization.ipynb
│   ├── 05_modeling_churn.ipynb
│
├── sql/
│   ├── customer_metrics.sql
│   ├── churn_analysis.sql
│   └── cohort_analysis.sql
│
├── src/                    # reusable code (THIS MAKES YOU PRO)
│   ├── __init__.py
│   ├── data_cleaning.py
│   ├── feature_engineering.py
│   ├── utils.py
│
├── dashboards/
│   ├── powerbi/
│   │   └── customer_churn_dashboard.pbix
│   └── exports/
│       └── dashboard_screenshots/
│
├── reports/
│   ├── business_report.pdf
│   ├── insights_summary.md
│   └── executive_presentation.pptx
│
├── configs/
│   └── config.yaml
│
├── requirements.txt
└── .gitignore

