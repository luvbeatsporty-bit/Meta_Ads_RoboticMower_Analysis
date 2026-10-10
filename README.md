# Meta Lead Ads Performance Analysis Project (FJD B-End Mower Business)

## Project Overview

This project provides a comprehensive data analysis and performance review of Meta Lead Ads campaigns for FJD's B-end robotic mower business. Spanning a continuous 11-week period, the analysis evaluates core advertising metrics including spend, impressions, link clicks, and potential customer leads to optimize marketing efficiency and drive better customer acquisition strategies.

## Key Features & Objectives

1. Campaign Performance Review:** Analyze weekly trends in advertising spend, reach, engagement, and lead generation.
2. Efficiency Benchmarking:Compare cost-per-lead (CPL) and conversion metrics across different countries, regions, and specific product model campaigns.
3. Data Standardization:Establish robust data cleaning pipelines and standardized KPI definitions to ensure reporting accuracy and reproducibility.
4. Optimization Roadmap:Deliver data-driven insights and priority recommendations to optimize future ad spend and audience targeting.


## Project Structure

```text
├── data/
│   ├── raw/                 # Original weekly reports exported from Meta Ads Manager
│   └── processed/           # Cleaned and standardized datasets ready for analysis
├── notebooks/               # Jupyter Notebooks for exploratory data analysis and modeling
├── reports/                 # Generated summary reports, charts, and presentations
└── README.md                # Project documentation

```

## Data Pipeline & Quality Control

1. Data Collection & Aggregation:Consolidated raw weekly performance spreadsheets into a unified master dataset.
2. Quality Checks:Systematically audited column types, missing values, anomalies, and reporting date ranges. Minor outliers were properly tagged and handled.
3. Data Cleaning & Standardization:**
* Standardized numeric formats and null-value handling rules.
* Defined consistent formulas for key metrics (e.g., CPL, Link CTR, Click-to-Lead Rate, CPC, CPM).
* Implemented standardized product model extraction rules to accurately categorize campaigns by specific hardware models and application scenarios.



## Core Metrics & KPIs

1. Spend: Total capital invested in Meta Lead Ads.
2. Impressions & Clicks:** Ad visibility and user engagement measured via Link CTR.
3. Leads: Number of prospective customer inquiries generated.
4. CPL (Cost Per Lead):** Acquisition efficiency metric calculated as total spend divided by total leads.
5. Click-to-Lead Rate: Conversion efficiency measuring how many link clicks successfully converted into submitted leads.


## Weekly Trend Analysis

1. Established macro baseline performance metrics across the entire 11-week window.
2. Tracked weekly fluctuations in budget allocation, click volumes, lead generation, and cost variations along a chronological timeline.


## Getting Started

To run the analysis scripts or reproduce the reports:

1. Clone this repository.
2. Install dependencies:
```bash
pip install -r requirements.txt

```


3. Place raw report files into the `data/raw/` directory and run the data preprocessing script.

---

## License

This project is proprietary and confidential to FJD.
