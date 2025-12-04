# Analysis and Visualization of Advertising Campaigns 2021

## Dataset

- ad_date
- campaign_name
- total_spend
- total_impressions
- total_clicks
- total_value
- cpc
- cpm
- ctr
- romi

## Technologies Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## Data processing
- **Missing values:** (NaN) were replaced with 0
- **Date conversion:** date columns were converted to datetime format
- **Sorting:** data was sorted by date
- **Grouping:** data was grouped by date or campaign for analysis

## Visualizations
- **Line charts** - trends of spend and ROMI (aggregated by date)  
- **Bar plots** - trends of spend and ROMI (aggregated by campaign)  
- **Heatmap** - correlation analysis between metrics  
- **Boxplots** - distribution of ROMI by campaign  
- **Histograms** - comparison of values across groups  
- **Scatterplots with linear regression** - relationship between spend and revenue

# Advertising Campaign Analysis
  ## Overall Trends in Spending and ROMI
   - Advertising spending changed over time and was not stable.
   - ROMI stayed stable in most periods, with an average of about 1.25.
   - There is a strong direct correlation between spending and revenue, but this works only for **small and medium spending.**
  ## Spending Distribution by Campaign
   - Most of the budget was focused on these campaigns: **Lookalike, Electronics, and Wholesale.**
   - These campaigns are stable and show medium ROMI with the smallest variation:
       - Lookalike: 1.1 - 1.4  
       - Wholesale: 1.1 - 1.3  
       - Electronics: 0.9 - 1.4
   - The **Trendy** campaign is very effective, with ROMI between 1.6 - 2.1, and ROMI is quite stable.
   - The **Promos** campaign also shows high ROMI (1.75 - 1.85), but it has a large variation and some outliers.
  ## Conclusions About Campaign Effectiveness
   - **Medium ROMI and stability:** Lookalike, Wholesale, Electronics - low risk and predictable results.
   - **High ROMI but risky:** Promos - higher revenue, but with bigger variation and possible outliers.
   - **High ROMI with low spending:** Trendy - most likely linked to a product or promotion that had high demand without extra advertising costs.
   - **Budget optimization:** investing in Lookalike and Wholesale gives stable profit, while Trendy and Promos can be used to increase revenue, but spending should be controlled to avoid lower effectiveness when costs rise.

