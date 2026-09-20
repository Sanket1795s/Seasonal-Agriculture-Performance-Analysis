# Seasonal Agriculture Performance Analysis

**VOIS AICTE Batch 2026–2027 — Major Project (Data Analytics)**

## Objective
Analyze agricultural performance data across three cropping seasons — **Kharif, Rabi, and Zaid** — to identify meaningful seasonal patterns, trends, relationships, and differences in agricultural outcomes, and derive evidence-based insights and recommendations for seasonal agricultural planning.

## Dataset
- 4,000 farm-level records across 8 Indian states and 8 crops
- Features: environmental conditions (rainfall, temperature, humidity, soil moisture), farming inputs (fertilizer, pesticide, irrigation method, water use), and outcomes (yield, production, revenue, cost, profit, disease/pest risk)

## Key Findings
- **Kharif is the strongest season overall** — highest rainfall/humidity, highest crop-adjusted yield, and by far the highest average profit (~₹1.79 lakh)
- **Zaid is the weakest, often loss-making season** — lowest yield, highest water use despite lowest rainfall, lowest water efficiency, and a **negative average profit** (~₹-24,805)
- Raw yield comparisons can mislead — Sugarcane's high yield scale masks a real, statistically significant seasonal decline that only appears once crop mix is controlled for
- **Drip irrigation** consistently outperforms **Flood irrigation** on both water efficiency and profit, in every season
- **Sugarcane and Chilli** are profitable in every season; **Wheat and Rice** run at a loss in every season
- All key seasonal differences (profit, water efficiency, disease risk, crop-adjusted yield) are statistically significant (ANOVA, p < 0.05)

## Tools & Technologies
Python 3 · Pandas · NumPy · Matplotlib · Seaborn · SciPy (stats) · Jupyter Notebook

## Repository Contents
- `Seasonal_Agriculture_Performance_Analysis.ipynb` — full analysis notebook (data cleaning, EDA, statistical testing, insights)
- `Seasonal_Agriculture_Performance_Analysis.pdf` — PDF export of the notebook
- `seasonal_agriculture_performance_dataset.csv` — source dataset

## How to Run
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
jupyter notebook Seasonal_Agriculture_Performance_Analysis.ipynb
```

## Author
[Your Name] — AICTE STU ID: [Your ID] — [Your College Name]
