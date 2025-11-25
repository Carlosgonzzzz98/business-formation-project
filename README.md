# Business Formation Statistics
## Overview
This project analyzes the U.S. Census Bureau’s Business Formation Statistics (BFS) for August 2025.  
The goal is to explore patterns in new business applications, identify interesting or unusual insights, and build a simple machine learning model that predicts future trends.

This project follows the CRISP-DM framework:

1. Business Understanding  
2. Data Understanding  
3. Data Preparation  
4. Exploratory Analysis  
5. Modeling  
6. Evaluation  
7. Predictive Scenario  
8. Conclusions  

---

## Files in This Repository

### `bfs_analysis.ipynb`
Contains the full analysis workflow, including:

- Data cleaning and preparation  
- Exploratory visualizations  
- A linear regression model  
- Model evaluation  
- A “what if” predictive scenario  
- Final takeaways  

### `Data/business_applications.xlsx`
The dataset used for this project, sourced from the U.S. Census Bureau’s Business Formation Statistics release.

---

## Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- openpyxl  

---

## Key Findings
- **The South** recorded the highest total business applications in August 2025.  
- **Corporate applications in the Midwest** climbed +23.9%, indicating possible regional expansion by larger firms.  
- **Planned-wage applications** dropped sharply (−7.8%), suggesting delayed hiring or leaner business launches.  
- The machine learning model performed extremely well (**R² ≈ 0.999; MAE ≈ 1,800**) because August values are mathematically tied to July values and percent changes.  
- A predictive scenario showed that increasing Midwest momentum produced further growth, reinforcing regional acceleration.

---

## Motivation
Business formation data is an early indicator of economic confidence, entrepreneurship, and regional shifts.  
Even with a small dataset, applying a structured data science process can uncover meaningful trends that tell a story about where economic momentum is heading.

---

## Blog Post Summary (Non-Technical)
A readable, stakeholder-friendly summary of this project is available here:

👉 **Medium Article:**  
https://medium.com/@carlosgonzzzz98/what-business-applications-in-august-2025-reveal-about-the-future-of-entrepreneurship-8a7e4815d473

---

## How to Run the Notebook

1. Make sure the file is in:  
   `Data/business_applications.xlsx`
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
   
## Acknowledgements
- U.S. Census Bureau — Business Formation Statistics
- Course instructors for guidance
- Open-source Python community for the libraries used
  
---
