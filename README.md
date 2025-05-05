# Zomato
 Zomato Restaurants Expansion Analysis
 🧩 Problem Statement
As a consultant data analyst for Zomato, the goal is to identify strategic insights for expanding Zomato’s footprint by suggesting new countries, states, cities, and restaurant types, based on detailed data analysis and visualization.

🗂️ Project Structure
Zomato Restaurants Analysis.pptx – Final presentation with visuals and recommendations.

Sidharth zomato.docx – Full report documenting methodology, Excel formulas used, and business insights.

Zomato_Expansion_Analysis.xlsx (not uploaded but referenced) – Main analysis file with raw data, transformations, and charts.

📌 Key Analyses & Insights
1. Data Cleaning
Converted inconsistent date formats using DATEVALUE and extracted DAY, MONTH, YEAR.

Filled missing values using median imputation for robustness.

Converted currencies using real-time Power Query + API integration.

Standardized currency names and formatted geographical data.

2. Geographical Insights
Used VLOOKUP to map country codes.

Counted restaurants per country/year using COUNTIF.

Suggested new markets with less competition but promising ratings: Australia, Canada, Singapore, Sri Lanka.

3. Competitor Analysis
Used pivot tables to identify:

Top competitors (high rating and cost).

Low-rated restaurants as benchmarks to avoid.

4. Cuisine & Service Strategy
Recommended cuisines based on high-rating correlation (e.g. Italian, Seafood, Bakery).

Suggested adding table booking and online delivery features as differentiators.

5. Pricing Strategy
Analyzed price distribution using histograms.

Average and total cost analyzed by country using AVERAGEIF, SUMIF.

📈 Visualizations Used
Line Charts – Country-level competition.

Pivot Tables – State/city breakdown.

Waterfall Charts – Country rating trends.

Pie Charts – Spending distribution.

Histograms – Price range distribution.

🛠️ Excel Functions Applied
VLOOKUP

COUNTIF, COUNTIFS

AVERAGEIF

SUMIF

TEXT, DAY, YEAR, MONTH

Power Query for live currency rates

📍 Recommendations
Launch in underserved countries with moderate ratings and demand.

Focus on localized cuisines.

Offer online delivery & table booking in regions lacking such features.

Perform cost-controlled expansion based on current expenditure data.


