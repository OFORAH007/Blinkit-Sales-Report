# Blinkit Grocery Data Analysis Report


## Table of Content
- [Project Overview](#Project-Overview)
- [Objective](#Objective)
- [Tools Used](#Tools-Used)
- [Dataset Description](#Dataset-Description)
- [Data Preparation](#Data-Preparation)
- [Key Insights](#Key-Insights)
- [Actionable Findings](#Actionable-Findings)
- [Optimization & Recommendation](#Opimization-&-Recommendation)
- [Unexpected Outcome](#Unexpected-Outcome)
- [Visualization](#Visualization)
- [Limitations](#Limitations)
- [Future Improvement](#Future-Improvement)
- [About Me](#About-Me)
- [Conclusion](#Conclusion)


### Project Overview
This project provides a comprehensive analysis of BlinkIT's grocery data to derive insights that support sales performance optimization, customer satisfaction, and inventory planning. The dataset includes product details, outlet characteristics, and sales metrics across various item types and store formats.

<img width="1707" height="853" alt="Screenshot 2025-07-10 141142" src="https://github.com/user-attachments/assets/bae2a21e-b610-4e5c-b98c-cbe6694da22e" />


### Objective
To explore and analyze sales and product data from BlinkIT, with the goal of identifying:
- Key sales drivers and optimization opportunities
- Outlet-wise performance trends
- Actionable insights to improve marketing and supply chain strategies

### Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Microsoft Excel
- Power BI (for further dashboard visualization)
- Azure SQL Database studio [Download](https://learn.microsoft.com/en-us/azure-data-studio/download-azure-data-studio?tabs=win-install%2Cwin-user-install%2Credhat-install%2Cwindows-uninstall%2Credhat-uninstall)
- Github(Project Documentation & Portfolio)[Access](https://github.com/)


### Dataset Description
The dataset contains 8,523 entries across the following attributes:
- Item Fat Content, Item Type, Item Weight, Item Visibility
- Outlet Type, Outlet Size, Outlet Location Type
- Outlet Establishment Year, Sales, and Rating


### Data Preparation
- No major transformation were made.
- No missing Value or duplicate entries
- Introduce data dictionary for stakeholder's clarity.
- Harmonized Item Fat Content entries (e.g., low fat, LF standardized to Low Fat)
  
<img width="1659" height="869" alt="Screenshot 2025-07-13 094520" src="https://github.com/user-attachments/assets/c0e9df28-008a-449b-b9d8-4e11221a2f9b" />


## <u>Key Insights<u>

### Actionable Findings
1. Outlet Type Impact: Supermarket Type1 outlets contribute the highest sales volumes consistently across multiple item categories.
2. High Sales Drivers are Medium outlet size locations in Tier 2 areas and also Items with higher ratings (4.5–5.0) significantly outperform others.
3. "Fruits and Vegetables", "Dairy", and "Snack Foods" lead sales, suggesting high demand for fresh and quick-consumption products.

### Optimization & Recommendation
1. Increase ad placements and discounts for top-performing categories during high-traffic times (e.g., weekends, holidays).
2. Rating-Sales Correlation: High-rated products could be prioritized in promotions.
3. Allocate more marketing resources, logistics support, and product variety to Tier 3 cities as they show strong sales despite often being underdeveloped markets.
4. Use Supermarket Type 1 as the flagship model for future store rollouts. Tailor marketing campaigns and exclusive product launches through this channel.
5. Maintain or slightly expand low fat product lines especially in high-performing areas, but test the growth of regular fat offerings in health-conscious zones (e.g., Tier 2).

### Unexpected Outcome
1. Some low visibility items (<0.01) still managed strong sales, indicating possible promotional campaigns or seasonal demand surges.


### Visualisations
Key visuals created include:
- Single Value Cards/KPIs: For Total Sales, Average Sales, Number of Items, Average Ratings
- Area Chart: For Outlet Establishment
- Donut Chart: For Fat Content
- Bar Charts (Horizontal): For Fat by Outlets, Item Types, Outlet Types.
- Stacked Bar Chart (Horizontal): Outlet Size.
- Visuals available in my Github repository's Visualizations folder.


### Limitations
- No time-series data to analyze seasonality.
- Rating appears skewed (mean ~4), possibly not a true customer review metric.
  

### Future Improvement
- Integrate time-based sales data for trend and seasonality analysis.
- Use external data (e.g., weather, location demographics) for demand forecasting.
- Expand analysis with real-time sales dashboards using Power BI or Tableau
- Build a predictive sales model using regression and ensemble methods.
- 

### About Me 
I am Oforah Chukwudumeje a  passionate data analyst experieced in turning raw data into business intelligence using programming languages (Python and SQL) and visualization tools (Excel, Power BI & Taleau). I specialize in Data Cleaning, Data Visualization and story telling and I am also certified in Power BI, Advanced Excel, SQL [ACCESS](https://1drv.ms/f/c/dda1fced96c7fa03/Er93RtX479RDgV6BSIuKDFQBzyjDgV_RzQmG0dnH043QxA?e=vyuuLO)
[Linkedin - Link me up](https://www.linkedin.com/in/oforah/)
[Github - Connect with me](https://github.com/oforah007)
[Email - chukwudumejeoforah@gmail.conm]


### Conclusion
The BlinkIT dataset reveals that strategic visibility, high product ratings, and outlet characteristics directly influence sales performance. With deeper integration of time-based and customer-level data, the analysis can be expanded into predictive and prescriptive insights to drive growth.
