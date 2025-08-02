# Sales Insights for a Regional Retail Chain

## Business Case

A regional retail chain operating under the Simba Supermarket brand across Kigali seeks to:

- Identify top revenue-driving by product lines
- Evaluate branch-level performance and discover under/over-performers
- Uncover monthly trends and seasonal fluctuations  
- Make data-backed decisions on marketing and inventory  

## Project Workflow

## Step 1: Data Cleaning & Preparation

- Checked for nulls and duplicates — none found
- Converted Date and Time to proper datetime format
- Engineered features like Month, Weekday, Hour, and revenue in Rwandan Francs (RWF)
  using an exchange rate of 1 USD = 1,440 RWF
  


## Step 2: Exploratory Data Analysis (EDA)

Business Question(1)
- What are the top-selling products?
  Sports and Travel leads, followed by Electronics and Food & Beverages

Action(1)
- Prioritize stock and marketing for these categories

Business Question(2)
- Are there seasonal patterns?
  January shows peak revenue, dip in February

Action(2)
- Offer discounts or campaigns during slow months


Business Question(3)
- Which branches are strongest?
  Simba-Kicukiro, followed by Gikondo and Kigali Heights

Action(3)
- Support lower-performing stores with training or promos

Business Question(4)
- Member vs. Normal Customers?
  Members generate more revenue

Action(4)
- Strengthen loyalty and rewards programs

Business Question(5)
- Gender trends?
  Females spend more than males
  
Action(5) 
- Consider targeted promotions to female shoppers

## Folder Structure

retail-sales-analysis/
│
├── data/
│   └── sales_data_retail_project.csv
│
├── notebooks/
│   └── 01_exploration.ipynb
│
├── visuals/
│   ├── revenue_by_product.png
│   ├── monthly_sales_trend.png
│   ├── branch_performance_by_revenue.png
│   └── revenue_by_customer.png
│
├── PowerBI/
│   └── Simba_Sales_Report.pbix
│
└── README.md

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Power BI
- Git/GitHub

## Collaborators
Project by Eric Ntore(GitHub:Erico1118)





