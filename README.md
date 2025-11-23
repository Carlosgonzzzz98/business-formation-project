# Business Formation Statistics — Data Analysis Project

## Overview
This project studies the U.S. Census Bureau’s Business Formation Statistics (BFS) for August 2025.  
The goal is to gain insight into patterns in new business applications, identify unusual insights, and build a simple machine learning model that predicts future trends.

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
The main Jupyter notebook containing:

- Data cleaning and preparation  
- Exploratory visualizations  
- A linear regression model  
- Predictive scenario  
- Final conclusions  

### `Data/business_applications.xlsx`
The dataset used for the project, sourced from the U.S. Census Bureau’s Business Formation Statistics release.

---

## Libraries Used
The following Python packages are used in this analysis:

- pandas  
- numpy  
- matplotlib  
- scikit-learn  
- openpyxl (Excel reader)  
- seaborn (optional for styling)

---

## Key Findings
- The South had the highest total number of business applications in August 2025.  
- Corporate applications in the Midwest increased sharply (+23.9%), signaling regional expansion by larger firms.  
- Planned-wage applications fell significantly (−7.8%), reflecting postponed hiring or leaner business models.  
- A simple machine learning model achieved very high performance (R² ≈ 0.999), because July counts mathematically drive August counts.  
- A predictive scenario showed continued growth in the Midwest when percent change was artificially increased.

---

## Motivation
Business formation is a strong indicator of economic confidence, entrepreneurship, and regional economic shifts.  
This project illustrates that even with a small dataset, valuable insights can be discovered using a structured data science approach.

---

## How to Run the Notebook

1. Place `business_applications.xlsx` inside a folder named `Data`.  
2. Run the notebook top-to-bottom in Jupyter.  
3. Ensure `openpyxl` is installed:

    ```bash
    pip install openpyxl
    ```

---

## Acknowledgements
- U.S. Census Bureau for providing the BFS dataset  
- Course instructors for project guidance  
- Python open-source community for analytical tools  
