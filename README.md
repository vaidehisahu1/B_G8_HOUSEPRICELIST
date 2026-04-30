# US House Price Analysis Across 10 States

A data-driven analysis of the US residential real estate market using Python and Tableau.  
This project explores pricing patterns, price-per-square-foot efficiency, and listing behavior across 10 states.

---

## Overview

The US housing market lacks a consolidated cross-state analytical view, making investment and pricing decisions inefficient.  
This project builds an end-to-end data pipeline and interactive dashboards to uncover actionable insights.

- Dataset: 11,410 listings
- Time period: Aug 16 – Sep 1, 2024
- States covered: 10
- Tools: Python, Pandas, Jupyter, Tableau

---

## Problem Statement

How do house prices, price per sqft, and listing activity vary across states, cities, brokers, and time — and what patterns can guide investment and listing decisions? :contentReference[oaicite:0]{index=0}

---

## Tech Stack

- Python (Pandas, NumPy)
- Jupyter Notebooks
- Tableau
- Git & GitHub

---

## Project Structure
├── data/
│ ├── raw/
│ └── processed/
├── notebooks/
│ ├── 01_extraction.ipynb
│ ├── 02_cleaning.ipynb
│ ├── 03_eda.ipynb
│ ├── 04_statistical_analysis.ipynb
│ └── 05_final_load_prep.ipynb
├── dashboards/
|-- reports/
├── README.md
└── requirements.txt


---

## ETL Pipeline

The project follows a structured pipeline:

1. Data Extraction  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Statistical Analysis  
5. Final Data Preparation  

Feature engineering includes:
- `price_per_sqft`
- `weekday`
- `is_weekend`

---

## Key KPIs

- Total Listings: 11,410  
- Average Price: $975,188  
- Avg Price per Sqft: $515.3  
- Avg Bedrooms: 3.25 :contentReference[oaicite:1]{index=1}  

---

## Key Insights

- California dominates pricing and skews national averages ($1.16M avg). :contentReference[oaicite:2]{index=2}  
- North Carolina has the highest price-per-sqft efficiency ($684). :contentReference[oaicite:3]{index=3}  
- 73% of listings are published Thursday–Friday. :contentReference[oaicite:4]{index=4}  
- Weekend listings are ~21% cheaper than weekdays. :contentReference[oaicite:5]{index=5}  
- Price is more dependent on location than size (sqft correlation is moderate). :contentReference[oaicite:6]{index=6}  

---

## Tableau Dashboards

### 1. Geographic Overview
- State-wise price comparison
- Listings distribution
- Price per sqft analysis

### 2. Broker & Operational Analysis
- Broker performance
- Listing trends by day
- Market concentration

### 3. Market Trends & Distribution
- Price trends over time
- Distribution analysis
- Weekend vs weekday comparison

---

## Business Recommendations

- Invest in North Carolina and Washington for better returns at lower entry cost  
- Publish listings on Thursday mornings for maximum visibility  
- Target Alabama and Illinois for affordable housing initiatives :contentReference[oaicite:7]{index=7}  

---

## Limitations

- Short time window (17 days)
- Listing price ≠ final sale price
- California over-representation
- Limited weekend data

---

## Future Scope

- Extend dataset to 12 months
- Build predictive pricing models
- Integrate real-time data pipelines
- Add macroeconomic factors (interest rates, income data)

---

## Team

- Aditya Shankr  
- Arhan Alam  
- Jatin Kumar  
- Niharika Choudhary  
- Saransh Singh Tomar  
- Vaidehi Sahu  

---

## Repository

GitHub: https://github.com/vaidehisahu1/B_G8_HOUSEPRICELIST

---

## How to Run

```bash
git clone https://github.com/vaidehisahu1/B_G8_HOUSEPRICELIST.git
cd B_G8_HOUSEPRICELIST
pip install -r requirements.txt

