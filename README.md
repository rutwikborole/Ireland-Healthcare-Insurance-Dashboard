# Healthcare Insurance Dashboard: Insights from Ireland Health Insurance Data

<img width="1130" alt="Healthcare Dashboard" src="https://github.com/user-attachments/assets/bc14f1fc-f709-45df-9638-d788d2ea04b3" />

## Introduction
Welcome to the Healthcare Insurance Dashboard, a powerful Power BI visualization tool built to unravel the complexities of healthcare data in Ireland. This project leverages a comprehensive dataset spanning from 1958 to 2004, offering a deep dive into hospital charges, surgical trends, and the impact of lifestyle factors like smoking. Whether you're a healthcare professional, data analyst, or policy maker, this dashboard provides actionable insights to inform resource allocation, cost management, and public health strategies. Explore the interactive visuals and uncover the story behind Ireland's healthcare landscape!

## Dashboard Overview
This Power BI dashboard transforms raw healthcare insurance data into intuitive visualizations, enabling users to analyze trends, compare metrics, and filter data dynamically. The dataset includes key fields such as `charges`, `city_tier`, `hospital_tier`, `year`, `smoker`, and `state_id`, providing a robust foundation for in-depth analysis.

### Key Visualizations
- **Total Hospital Charges Per City Tier (1960-2000)**
  - *Visual*: Area chart
  - *Details*: Tracks charges across Tier 1, Tier 2, and Tier 3 cities, with Tier 1 peaking at $0.8M in certain years.
  - *Insight*: Urban areas (Tier 1) drive higher healthcare costs, likely due to increased demand or advanced facilities.

- **Total Charges Per Hospital Tier**
  - *Visual*: Bar chart
  - *Details*: Compares charges across hospital tiers, with Tier 1 hospitals (e.g., R011 at $6.4M) leading, followed by Tier 2 and Tier 3.
  - *Insight*: Specialized Tier 1 hospitals are the primary cost centers, highlighting their critical role in healthcare delivery.

- **Yearly Growth and Decline in Hospital Tier Counts**
  - *Visual*: Bar chart
  - *Details*: Shows a 99-tier increase in 2004, with a 3-tier decrease and 22 other changes, indicating infrastructure expansion.
  - *Insight*: The 2004 surge suggests a strategic push to enhance healthcare capacity.

- **Number of Major Surgeries**
  - *Visual*: Pie chart
  - *Details*: Reveals 45.99% of cases with no surgeries, 32.32% with one, and smaller shares for two or more.
  - *Insight*: Preventive care or minor procedures dominate, with major surgeries being less common.

- **Healthcare Costs: Smokers vs. Non-Smokers Over Time**
  - *Visual*: Sankey diagram
  - *Details*: Non-smokers’ costs stabilize at $0.65M by 2000, while smokers’ peak at $0.88M in the 1980s before dropping to $0.5M.
  - *Insight*: Smoking significantly elevates costs, with a late-century decline possibly linked to health initiatives.

- **Key Metrics**
  - *Total Charges*: $31.53M
  - *Total Customers*: 2,329
  - *Insight*: These figures underscore the scale of healthcare expenditure and customer base analyzed.

## Interactive Features
- **Year Slider**: Filter data by year (1958-2004) for temporal analysis.
- **Month Filter**: Drill down to monthly trends for granular insights.
- **Hospital Tier Filter**: Isolate data by Tier 1, Tier 2, or Tier 3.
- **Customizable Fields**: Explore `charges`, `city_tier`, `smoker`, and more dynamically.

## Problem Solved and Business Value
- **Problem Addressed**:
  - Healthcare organizations often struggle with understanding cost drivers, optimizing resource allocation, and identifying high-risk customer segments due to the sheer volume and complexity of insurance data. Without clear insights, businesses face challenges in predicting expenses, justifying infrastructure investments, and tailoring wellness programs effectively.
  - This dashboard solves these issues by providing a centralized, interactive platform to analyze historical trends, segment costs by city and hospital tiers, and correlate lifestyle factors (e.g., smoking) with healthcare expenses.

- **Business Benefits**:
  - **Cost Management**: Identifies high-cost areas (e.g., Tier 1 cities and hospitals) to optimize budgeting and negotiate better rates with providers.
  - **Strategic Planning**: Supports infrastructure decisions, such as the 2004 tier expansion, by highlighting growth trends and capacity needs.
  - **Customer Insights**: Enables targeted interventions (e.g., anti-smoking campaigns) by quantifying the financial impact of smoker-related costs.
  - **Competitive Advantage**: Empowers insurance companies to offer data-driven pricing models and personalized health plans, enhancing customer satisfaction and retention.
  - **Operational Efficiency**: Reduces manual data analysis time with real-time filters and visualizations, allowing teams to focus on strategy rather than data crunching.

## Technical Implementation
- **Tool**: Microsoft Power BI
- **Data Processing**: Cleaned and transformed using Power Query for accuracy.
- **Visuals**: Utilizes area charts, bar charts, pie charts, and Sankey diagrams.
- **Interactivity**: Enhanced with filters and slicers for user-friendly navigation.

## Actionable Insights
- **Resource Allocation**: Prioritize investments in Tier 1 cities and hospitals to address high charge volumes.
- **Public Health Campaigns**: Leverage the smoker cost disparity to promote anti-smoking initiatives.
- **Infrastructure Planning**: Use the 2004 tier growth trend to forecast future healthcare facility needs.

## Future Enhancements
- Integrate regional health policies or demographic data for richer context.
- Add predictive models to forecast costs and tier expansions.
- Enhance visuals with tooltips and drill-down options for deeper exploration.

## Repository Contents
- `Healthcare_Insurance_Dashboard.pbix`: The Power BI dashboard file.
- `data.csv`: Anonymized raw dataset.
- `README.md`: This documentation.

## Get Involved
This project is open for collaboration! Fork the repository, suggest improvements, or submit pull requests. Your contributions can help refine the dashboard and unlock new insights. Issues and feedback are warmly welcomed!
