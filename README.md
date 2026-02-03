# Trader Behavior & Market Sentiment Analysis

## Overview
This project analyzes crypto trader behavior by integrating **Hyperliquid trading data** with the **Fear & Greed Index** to understand how market sentiment influences trading volume, profitability, and risk behavior. The goal is to extract actionable insights using real-world data science workflows.

The project demonstrates end-to-end skills including data preprocessing, feature engineering, exploratory data analysis, visualization, and insight communication.

---

## Key Objectives
- Study the impact of market sentiment (Fear / Neutral / Greed) on trader performance  
- Compare trade volume, profitability, and PnL distribution across sentiment regimes  
- Analyze behavioral differences between overall traders and top-performing (smart money) traders  
- Present findings using clear, publication-quality visualizations  

---

## Project Structure
ds_sanskar_kocharekar/
├── notebook_1.ipynb # Core analysis and EDA
├── notebook_2.ipynb # Advanced & smart-money analysis
├── csv_files/ # Raw and processed datasets
├── outputs/ # Generated charts and plots
├── ds_report.pdf # Final summarized insights
└── README.md

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Google Colab  
- Jupyter Notebook  

---

## Setup (Google Colab)

1. Open Google Colab: https://colab.research.google.com  
2. Create the required folders:

import os
os.makedirs("/content/ds_sanskar_kocharekar/csv_files", exist_ok=True)
os.makedirs("/content/ds_sanskar_kocharekar/outputs", exist_ok=True)

ds_sanskar_kocharekar/csv_files/

---

How to Run

Open notebook_1.ipynb and run all cells top to bottom

Performs data cleaning, feature engineering, EDA, and core visualizations

Open notebook_2.ipynb and run all cells

Contains advanced strategy analysis and smart-money comparison

All generated plots are saved automatically in:

ds_sanskar_kocharekar/outputs/
