# Best Performing Stores Analysis – Tableau Project

## Overview
This Tableau project analyzes store performance for a laundry pick-up service startup operating in 150 locations, including 10 newly opened stores. The analysis compares the performance of two sales regions and identifies which new stores have the best potential for further marketing investment.

## Objectives
- Implementing a strategic approach to store analysis by **classifying stores into two regions** and using Tableau for performance comparison.
- Compare **Average Revenue**, **Average Marketing Spend**, and **Return on Marketing Investment (ROMI)** between the two sales regions.
- Identify **top-performing new stores** for strategic marketing investment.
  
## Methodology
1. **Data Preparation**
   - Used store-level data including Store ID, City, State, Sales Region, Marketing Spend, Revenue, and Population.
   - Classified stores into Region 1 and Region 2 for comparison.

2. **Exploratory Analysis**
   - Regional comparison using Tableau’s map charts and calculated fields for average revenue, spend, and ROMI.

3. **Advanced Analytics**
   - Applied **K-means clustering** to group stores by marketing spend vs. revenue performance.
   - Incorporated **population data** into clustering for deeper insights.
   - Conducted **trend line analysis** to quantify revenue generated per marketing dollar in each cluster.
   - Identified the **top three revenue-generating stores per marketing dollar spent**.
   
## Key Findings
- **Region 1** outperforms Region 2 with higher average revenue, lower marketing spend, and higher ROMI.
- K-means clustering revealed three performance groups:
  - **Blue Cluster:** $7.32 revenue per $1 spent on marketing (highest ROI).
  - **Orange Cluster:** $3.17 revenue per $1 spent.
  - **Red Cluster:** $0.94 revenue per $1 spent (loss-making).
- The **blue cluster’s new stores** offer the best opportunity for increased marketing investment.

## Tools and Technologies
- **Tableau** – Data visualization and dashboard development.
- **Excel / CSV** – Data cleaning and preparation.
- **K-means Clustering & Trend Line Analysis** – For performance segmentation.

## Dashboard
View the live Tableau dashboard here: [**Tableau Public Link**](https://public.tableau.com/app/profile/parth.milind.bhingarde/viz/CaseStudyLaundry/DevicePreviewDash)

## Report
Read the full project report here: [**Google Docs Report**](https://drive.google.com/file/d/1OXEAGd_BVQna-yE00EoK_BkkpJDMKiHK/view?usp=drive_link)

## Conclusion
Focusing marketing budgets on blue-cluster stores—especially newly opened ones—can maximize revenue returns. The analysis demonstrates the value of combining **geographical segmentation, clustering, and ROI-based trend line evaluation** for data-driven marketing strategies.

## Future Improvements
- Incorporate time-series forecasting to predict store performance trends.
- Include customer demographics to refine targeting.
- Automate data refresh and Tableau dashboard updates.

---
