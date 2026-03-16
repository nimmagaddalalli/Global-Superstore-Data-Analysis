# Global Superstore Data Analysis(2011--2014)

## 📌 Project Overview

This project performs a detailed analysis of the Global Superstore dataset, including sales, profit, product affinity, customer retention, and cross-selling opportunities.
The goal is to generate actionable business recommendations and
demonstrate end-to-end data analytics capabilities.

------------------------------------------------------------------------

## 🎯 Business Objectives

-   How are sales and profit trending over time?
-   Which categories and sub-categories generate the most and least profit?
-   How do discounts impact profitability?
-   Which regions and markets perform best and worst?
-   Does shipping cost affect profit margins and delivery?
-   Customer retention and purchase patterns over 2011-2014?
-   Product affinity and cross-selling opportunities?
-   Sales prediction using temporal and seasonal features?

------------------------------------------------------------------------

## 🛠 Tools & Technologies

-   Python (Pandas, NumPy, Matplotlib, Seaborn, Pathlib, dotenv, Anthropic)
-   Jupyter Notebook
-   PowerBI
-   Claude AI (for analytical interpretation & business insights)

------------------------------------------------------------------------

## 📂 Project Structure

Global-Superstore-Data-Analysis/
│
├── data/
│   ├── raw/                    # Original raw dataset file
│   └── processed/              # Cleaned CSVs used in analysis
│
├── notebooks/
│   └── Global_Superstore_Project_Analysis.ipynb   # Main Jupyter notebook
│
├── outputs/
│   ├── figures/                # Python plots saved as PNG
│   └── tables/                 # Analysis tables saved as CSV
│
├── powerbi/
│   ├── Global_Superstore_Dashboard.pbix           # Power BI dashboard file
│   └── dashboard_screenshots/
│       ├── page1_executive_overview.png
│       ├── page2_product_insights.png
│       ├── page3_customer_analysis.png
│       └── page4_key_insights.png
│
└── README.md                   # Project documentation

------------------------------------------------------------------------
## 📂Folder details:

- data/raw/** – Original `.txt` file  
- data/processed/** – Cleaned CSVs ready for analysis  
- outputs/figures/** – Saved plots such as sales trends, profit trends, growth trends, and boxplots  
- outputs/tables/** – Summary tables such as profit by category, sub-category, market, customer retention, purchase frequency, product affinity, and cross-selling opportunities

------------------------------------------------------------------------

## 📊 Key Insights

- Sales & Profit Trends:** Sales grew strongly (~130% monthly growth), but profit volatility shows margin instability during high-revenue periods.  
- Category Performance:** Technology is the top profit driver, but negative impacts from some sub-categories affect overall margins.  
- Discount Impact:** Strong negative correlation (~-0.85) between discount and profit margin; discounts above 30% produce negative profits.  
- Regional Performance:** APAC is the strongest profit contributor (~$373K), while US shows high sales but weaker margins, highlighting operational inefficiencies.  
- Customer Metrics:** Retention improved from 67% → 82%, and purchase frequency increased from 1.56 → 2.25 orders/customer/year, boosting customer lifetime value.  
- Forecasting Accuracy:** Trend + seasonal forecasting achieved MAE ≈ $3.6K/day; more advanced models could further improve accuracy.  
- Key Optimization Levers:**  
  1. Discount control and pricing governance  
  2. Elimination/restructuring of loss-making sub-categories  
  3. Margin improvement in underperforming markets  

These actions can drive sustainable profit growth while maintaining revenue momentum.


------------------------------------------------------------------------

## 📊 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize key performance metrics, regional performance, product insights, and customer trends derived from the cleaned dataset.

### Dashboard Pages

1. **Executive Overview**
   - Total Sales
   - Total Profit
   - Profit Margin
   - Sales Trend Over Time
   - Regional Revenue Distribution

2. **Product Insights**
   - Profit by Category
   - Profit by Sub-Category
   - Discount vs Profit Impact
   - Product Performance Comparison

3. **Customer Analysis**
   - Customer Purchase Frequency
   - Customer Revenue Contribution
   - Repeat Customer Trends

4. **Key Business Insights**
   - Summary of major findings
   - Strategic improvement areas

### Dashboard Preview

#### Executive Overview
![Executive Overview](powerbi/dashboard_screenshots/page1_executive_overview.png)

#### Product Insights
![Product Insights](powerbi/dashboard_screenshots/page2_product_insights.png)

#### Customer Analysis
![Customer Analysis](powerbi/dashboard_screenshots/page3_customer_analysis.png)

#### Key Insights
![Key Insights](powerbi/dashboard_screenshots/page4_key_insights.png)

### Dashboard File
```
powerbi/Global_Superstore_Dashboard.pbix
```

The Power BI dashboard integrates insights from the Python analysis and provides an interactive interface for exploring sales performance, product profitability, and customer behavior.


------------------------------------------------------------------------


## 🤖 AI-Assisted Analysis

Claude AI was integrated within Jupyter to interpret the data analysis and provide strategic business recommendations

AI was used to interpret the results of the analysis and have a deeper understanding of the data. AI is not used to replace the data analysis


------------------------------------------------------------------------

## 📈 Business Recommendations

- **Discount Optimization**: +15% profit margin improvement
- **Shipping Efficiency**: +8% cost reduction in target markets
- **Cross-selling**: +12% average order value increase
- **Category Focus**: +20% improvement in underperforming segments

------------------------------------------------------------------------

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Global-Superstore-Data-Analysis.git

2. Create a .env file in the project root (if using AI Integration):

ANTHROPIC_API_KEY=your_api_key_here

3. Install required Python packages:

Pandas, NumPy, Matplotlib, Seaborn, Pathlib, dotenv, Anthropic

4. Open notebooks Global_Superstore_Project_Analysis.ipynb in Jupyter and run all cells.

5. All outputs (tables and figures) are automatically saved to the outputs/ folder.
------------------------------------------------------------------------

## 💡 Author

Lalitha Anusha Nimmagadda – Data Analyst with experience in retail analytics and Python-based data projects.  
Passionate about turning data into actionable business insights and creating reproducible, end-to-end data analysis workflows.

