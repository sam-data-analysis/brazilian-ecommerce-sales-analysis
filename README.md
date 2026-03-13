# Brazilian E-Commerce Sales Analysis

This project analyses transactional data from a Brazilian e-commerce platform to identify key revenue drivers, customer behaviour patterns, and strategic business opportunities.

The analysis focuses on product performance, geographic revenue concentration, pricing behaviour, seasonal demand, and customer revenue distribution.

The goal is to demonstrate how SQL and Python can be used together to generate actionable business insights for an online retail business.

## Featured Visualisation

<img src="revenue_heatmap.png" width="700">

## Project Highlights

- Analysed **112,650 transactions** from a Brazilian e-commerce platform
- Combined **SQL** for data extraction with **Python** for analysis and visualisation
- Identified strong revenue concentration in **São Paulo and Rio de Janeiro**
- Found that most purchases occur in the **£20–£100 price range**
- Showed that **Beauty & Health** was the strongest long-term growth category

## Supporting Visualisations

### Top 10 Cities by Revenue

<img src="top_cities_revenue.png" width="700">

### Monthly Revenue Trend

<img src="monthly_revenue_trend.png" width="700">

### Order Price Distribution

<img src="order_price_distribution_under_500.png" width="700">

### Customer Revenue Concentration

<img src="customer_revenue_pareto.png" width="700">

## Dataset

The dataset contains **112,650 transactions** from a Brazilian e-commerce platform.

### Key variables used in the analysis include:

| Variable | Description |
|----------|-------------|
| `order_date` | Date of purchase |
| `price` | Order item price |
| `product_category_name` | Product category |
| `customer_city` | Customer location |
| `customer_id` | Unique customer identifier |

The dataset includes approximately:

- **96,000 unique customers**
- **4,000+ cities**
- **Multiple product categories**

## Tools Used

• SQL – data extraction and table joins  
• Python (Pandas) – data cleaning and analysis  
• Matplotlib / Seaborn – data visualisation  
• Jupyter Notebook – analysis environment

## Key Questions

This analysis investigates several business questions:

- Which product categories generate the most revenue?
- Which cities drive the majority of sales?
- How do seasonal trends affect revenue?
- What price ranges do customers purchase most frequently?
- Is revenue concentrated among a small group of customers?

## Analysis Performed

The project includes the following analyses:

- Revenue by product category
- Monthly revenue trends
- Revenue by city
- Category growth over time
- Order price distribution
- Price band analysis
- Pareto analysis of revenue by city
- Revenue heatmap by category and month
- Customer revenue concentration analysis

## Key Insights

Several important patterns emerged from the analysis.

### Revenue Concentration

Sales are strongly concentrated in major metropolitan areas, particularly **São Paulo and Rio de Janeiro**, indicating that these cities form the retailer’s primary customer base.

### Pricing Behaviour

Most purchases occur within the **£20–£100 price range**, suggesting that the retailer primarily operates in the **low-to-mid price segment**.

### Category Growth

The **Beauty & Health** category demonstrates the strongest growth over time, indicating increasing demand within this segment.

### Customer Revenue Distribution

Approximately **40% of customers account for around 80% of revenue**., suggesting that the business relies on a broad customer base rather than a small number of high-value buyers.

### Seasonal Demand

Sales peaks appear around **Brazilian summer months and Mother’s Day**, indicating that seasonal events significantly influence purchasing behaviour.

## Business Recommendations

Based on the analysis, several strategic opportunities emerge:

- Prioritise marketing investment in high-revenue cities such as **São Paulo and Rio de Janeiro**
- Expand inventory in high-growth categories such as **Beauty & Health**
- Focus product offerings in the **£20-£100 price range**, where demand is strongest
- Align marketing campaigns with key seasonal retail events such as **Mother's Day**
- Invest in **customer acquisition strategies**, as revenue is distributed across a broad customer base

