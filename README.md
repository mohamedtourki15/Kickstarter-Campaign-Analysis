# Kickstarter-Campaign-Analysis

Analyze Kickstarter campaign data to identify the key factors influencing campaign success and funding performance across categories and countries.

# Approach
Cleaned raw data (handled missing values, duplicates, invalid entries)
Converted timestamps into usable datetime format
Created new features:
Campaign duration
Success indicator (0/1)
Funding ratio (pledged / goal)
Removed outliers using 99th percentile filtering
Performed EDA across:
Categories
Countries
Goals
Duration
Built visualizations including heatmaps and funding comparisons

# Key Insights
~67% of campaigns were successful
Lower funding goals → significantly higher success rate
Top performing categories:
Hardware
Drama
Mixed Media
Low-performing categories:
Web-based campaigns
The US dominates in both campaign volume and funding
Some categories show 100% success due to low sample size (important limitation)

# Business Insights
Not all categories perform equally across countries
Some categories are globally strong (Hardware)
Others are country-dependent (Ready-to-Wear)
Some categories show no activity in certain countries → potential opportunity

# Recommendations
Focus on high-success categories for safer campaigns
Start with realistic funding goals
Test new markets with small campaigns
Adapt strategy based on country-specific behavior

# Limitations
Some results are affected by small sample sizes
Dataset may not fully represent all Kickstarter campaigns

