## PROBLEM STATEMENT
Sales teams often lack a clear, data-driven understanding of regional performance, making it difficult to identify growth opportunities and optimize resources.
This project aims to analyse and visualize regional sales data to uncover trends, evaluate profitability, and support strategic decision-making.

**Objective**
- Leverage 5 years of historical data to pinpoint growth levers and optimize strategy.
- Analyze and visualize **sales KPIs** such as revenue, profit margin, and orders.  
- Identify **top-performing states, channels, and customers** driving business growth.  
- Surface trend, outliers & relationships.

### PROJECT OVERVIEW
This project performs **end-to-end Exploratory Data Analysis (EDA)** using python(pandas and numpy) and **Power BI Dahboard** of sales dataset.  
It focuses on **KPI tracking**, **sales performance**, and **performance monitoring**.

### PROJECT WORKFLOW
1. Define Objective and expected Outcomes.
2. Gather multi-source sales data (Excel sheets) and understand schema.
3. Data Collection and Cleaning - Imported the sales KPI dataset, dealt with missing values and dates, and removed duplicates.
4. Load into Colab for initial profiling and data understanding using Python.
5. Visualize trends, compare performance, and extract key insights.
6. Build Power BI dashboard and present strategic findings.

### CHARTS AND VISUALS
### Monthly Sales 
<img src="charts_and_visuals/Monthly%20Sales%20Trend.png" width="720">

#### INSIGHTS

* Consistent sales cycle: $24M to $26M.
* Seasonal peaks: Late spring/early summer (May-June).
* Annual low: January.
* Notable outlier: Sharp revenue drop in early 2024.

### Top Performing Products
<img src="charts_and_visuals/Top%2010%20Products%20by%20Revenue.png" width="720">

### INSIGHTS

* Revenue leaders: Products 26 & 25 dominate.
* Mid-range: Products 5, 13, 14, 15 show similar revenue.
* Bottom cluster: Products 1, 2, 3, 4 have the lowest revenue.
* Strategy: Grow mid-tier, improve lower performers.
  


### Top Performing States by Number of Order and Revenue
<img src="charts_and_visuals/Top%2010%20States%20by%20Number%20of%20Orders.png" width="720">

<img src="charts_and_visuals/Top%2010%20States%20by%20Revenue.png" width="720">


#### INSIGHTS
* California tops revenue & orders.
* IL, FL, TX: High in both.
* Revenue & orders linked.
* Other top states: Lower contribution.

### Sales Distribution Across Channels
<img src="charts_and_visuals/Total%20Sales%20by%20Channel.png" width="380" height="380">

#### INSIGHTS
* Wholesale dominates: Generates the majority of total sales at 54.1%.
* Distributor is significant: Contributes a substantial 31.3% to total sales.
* Export is a smaller portion: Accounts for 14.6% of the total sales.

### Average Order Value
<img src="charts_and_visuals/Distribution%20of%20Average%20Order%20Value.png" width="730">

#### INSIGHTS
* Low average order values are frequent.
* Distribution is right-skewed (long tail of high-value orders).
* Multiple order value clusters exist.
* Higher order values are not common.

### Top and Bottom 10 Customers by Revenue
<img src="charts_and_visuals/Top%20and%20Bottom%2010%20Customers%20by%20Revenue.png" width="720">

#### INSIGHTS
* Aibox Company leads significantly as the top revenue generator.
* Bottom 10 customers generate substantially low revenue (around $4-5M).
* Revenue concentration: Top customers drive a disproportionate share.
* Large gap: Exists between the revenue of top and bottom tier customers

### Customer Segmentation: Revenue vs. Profit Margin
<img src="charts_and_visuals/Customer%20Segmentation%20Revenue%20vsProfit%20Margin.png" width="500" height="380">

#### INSIGHTS
* Those Uniform 35–40 % margins confirm strong, consistent pricing and cost control.
* > $10 M clients with <36 % margins reveal discounting hotspots—re evaluate large‑account terms.
* $6–9 M clients with >40 % margins are high‑value candidates for targeted upsell.

### Total Sales by Region
<img src="charts_and_visuals/Total%20Sales%20by%20Region.png" width="680" height="480">

#### INSIGHTS
* West: Highest sales, strong market influence.
* South: Major sales contributor, key market area.
* Midwest: Steady sales performance, moderate market size.
* Northeast: Lowest sales, suggests need for deeper market understanding.

###  KEY INSIGHTS
* Pronounced Seasonality: January revenues average $124 M, dipping to $95 M in April.
* SKU Concentration: Products 26 & 25 together drive ~25 % of total sales.
* Channel Trade‑Off: Wholesale captures 54 % of volume; Export leads with ~38 % average margin.
* Geographic Dominance: California alone logs 7.6K orders ($230 M); the West region shows the largest swings.
* Aibox Company and State Ltd are the most valuable customers in terms of Revenue.

## RECOMMENDATIONS
* Seasonal Promotions: Launch recovery campaigns in April and amplify January offers to smooth revenue swings.
* SKU Optimization: Double down on top products 26 & 25 and re-evaluate pricing or phase out low‑margin SKUs
* Channel Expansion: Incentivize Export partnerships for high margins and introduce volume deals in Wholesale.
* Regional Investment: Replicate California’s success in other regions and boost marketing in the Northeast & Midwest.
* Margin Monitoring: Flag orders below 80 % margin and analyse cost drivers to uplift underperforming segments.









  












