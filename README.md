# 📱 Smartphone Market Data Analysis: Strategic Insights

## 📌 Project Overview

This project simulates a real-world business scenario where I acted as a **Lead Data Analyst** for a major gadget retail company. The objective is to analyze a comprehensive dataset of smartphone specifications to answer critical business questions and formulate data-driven sales strategies for the upcoming quarter.

This repository contains the end-to-end Exploratory Data Analysis (EDA) pipeline, from synthetic data generation with strategic outliers to advanced segmentation and visual storytelling.

**Program:** Google Developer Groups on Campus (GDGoC) Universitas Brawijaya 2026 - Machine Learning Study Jam (Chapter 1 Challenge).
**Achievement:** 100/100 (Best Participant).

## 🎯 Business Objectives

The analysis is structured around answering core business quests, including:

1. **Market Overview:** Understanding the distribution of smartphone prices and general statistical summaries.
2. **Brand Dominance:** Identifying the brand with the highest market share/volume in the catalogue.
3. **Extreme Specifications ("Storage Wars"):** Locating niche, maximum-capacity devices (e.g., 2TB storage) to understand the ceiling of current technology.
4. **Budget vs. Premium:** Analyzing the market spread from entry-level devices to luxury flagships, including outlier detection.
5. **Niche Market Segmentation:**
* **The Gaming Beast:** Filtering extreme performance devices (RAM > 12GB & Storage $\ge$ 512GB).
* **The Student Choice:** Finding highly-rated, budget-friendly devices (Price < 7 Million IDR & Rating > 4.5).


6. **Brand-Specific Analysis:** Sorting and segmenting specific brands (e.g., Apple) based on premium pricing hierarchies.

## 🛠️ Tech Stack & Tools

* **Programming Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## 📊 Dataset Generation

To mimic real-world retail data, a synthetic dataset of 150 smartphone models was generated using `Pandas` and `NumPy`.

* **Features Included:** `Brand`, `Model`, `RAM_GB`, `Storage_GB`, `Rating`, `Price_Juta`.
* **Pricing Logic:** Algorithmically generated based on RAM and Storage capacities with added random noise.
* **Data Anomalies:** Intentionally injected outliers (e.g., "Nokia 3310 Reborn" with 50.0 rating, or "Prototype X" with 128GB RAM at 1.0 Million IDR) to test data veracity and filtering robustness.

## 💡 Key Business Insights

1. **Market Fragmentation:** The market is highly fragmented with prices ranging from 1.0 Million to 30.4 Million IDR, showing a clear divide between volume-driven entry-level phones and high-margin premium devices.
2. **Brand Strategy:** **Google** dominates the catalogue volume (21 models), making it a prime candidate for mass promotional campaigns or bundling strategies.
3. **Targeted Segmentation Works:** The filtering pipeline successfully identified distinct consumer personas. For instance, the "Student" demographic has highly viable options (e.g., Oppo Phone 50, Vivo Phone 85) that offer maximum satisfaction (Rating > 4.5) at a constrained budget (< 7M IDR).

## 🚀 How to Run

1. Clone this repository:
```bash

git clone https://github.com/nadhif-royal/smartphone-market-data-analysis.git
```
2. Navigate to the project directory:
```bash
cd smartphone-market-data-analysis

```

3. Install the required dependencies:
```bash

pip install pandas numpy matplotlib seaborn

```
4. Open the Jupyter Notebook to explore the code and visualizations:
```bash
jupyter notebook Nadhif_Rifat_Rasendriya_Chapter1_Challenge.ipynb

```

## 👨‍💻 Author

**Nadhif Rif'at Rasendriya**

*Data Science & Product Management Enthusiast*

Connect with me on [LinkedIn](https://www.google.com/search?q=https://www.linkedin.com/in/royalnadhif50/)
