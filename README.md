# 🛒 Zepto Descriptive Analytics: Grocery Ordering Behavior Analysis

## 📌 Project Overview

This project performs **descriptive data analytics on grocery ordering behavior for Zepto**, an Indian quick-commerce platform. The objective is to analyze simulated order-level data to identify best-selling products, daily sales trends, peak ordering hours, category-wise customer satisfaction, delivery performance, city-wise engagement, and payment preferences.

Using Python-based data analysis and visualization, the project converts raw order records into meaningful business insights that can support inventory planning, delivery optimization, customer engagement, and marketing decisions.

**Important:** This project uses a synthetic dataset generated for academic and analytical purposes. The results represent simulated grocery-ordering behavior and should not be interpreted as actual or official Zepto business performance.

### 🎯 Project Highlights

- Analyzed **6,000 simulated grocery orders** across 30 days.
- Examined **18 grocery products**, 10 product categories, and 8 Indian cities.
- Identified the most frequently purchased products and peak ordering periods.
- Evaluated category-wise customer ratings and on-time delivery performance.
- Analyzed payment method preferences and customer age-group distribution.
- Derived actionable business recommendations from descriptive statistics.
- Established a foundation for future predictive analytics and demand forecasting.

---

## 📑 Table of Contents

1. [Business Problem](#-business-problem)
2. [Project Objectives](#-project-objectives)
3. [Dataset Description](#-dataset-description)
4. [Tools and Technologies](#-tools-and-technologies)
5. [Project Workflow](#-project-workflow)
6. [Data Cleaning and Preparation](#-data-cleaning-and-preparation)
7. [Key Performance Indicators](#-key-performance-indicators-kpis)
8. [Exploratory Data Analysis and Findings](#-exploratory-data-analysis-and-findings)
9. [Key Business Insights](#-key-business-insights)
10. [Business Recommendations](#-business-recommendations)
11. [How to Run the Project](#-how-to-run-the-project)
12. [Suggested Repository Structure](#-suggested-github-repository-structure)
13. [Limitations](#-limitations)
14. [Future Scope](#-future-scope)
15. [Conclusion](#-conclusion)
16. [References](#-references)
17. [Author](#-author)

---

## 💼 Business Problem

Quick-commerce businesses need to understand how customers purchase products, when demand increases, which product categories perform well, and where operational bottlenecks occur.

Without a structured analysis of order data, businesses may face challenges such as:

- Stock shortages for frequently purchased grocery items.
- Inefficient inventory allocation across dark stores.
- Insufficient delivery-partner availability during peak hours.
- Differences in delivery performance across product categories.
- Missed marketing opportunities in high-potential cities.
- Limited understanding of customer payment preferences.

This project addresses these challenges through descriptive analytics of simulated order-level data.

The analysis focuses on five central business questions:

1. Which grocery products generate the highest sales volume?
2. How does daily order volume change throughout the month?
3. Which hours experience the highest ordering activity?
4. Which product categories achieve the highest customer ratings and on-time delivery rates?
5. Which cities, customer age groups, and payment methods contribute most to ordering activity?

---

## 🎯 Project Objectives

The primary objective is to transform order-level data into meaningful insights about grocery purchasing behavior.

Specific objectives include:

- Identify the best-selling products based on units sold.
- Examine daily order-volume fluctuations and identify unusually high-demand days.
- Determine peak and low-demand ordering hours.
- Compare customer satisfaction across product categories.
- Evaluate the percentage of orders delivered within the 10-minute delivery target.
- Compare order volumes across eight cities.
- Analyze payment method preferences and customer age-group distribution.
- Calculate important business KPIs, including revenue, average order value, and order completion rate.
- Recommend operational and marketing improvements based on the results.
- Identify opportunities to extend the analysis into predictive modeling.

---

## 📊 Dataset Description

The project uses a synthetic Zepto order-level dataset generated using Python, NumPy, and Pandas.

### Dataset overview

| Attribute | Description |
|---|---|
| Dataset type | Synthetic, simulated order-level data |
| Analysis period | 1 July 2026 – 30 July 2026 |
| Duration | 30 days |
| Total orders | 6,000 |
| Delivered orders | 5,816 |
| Cancelled orders | 184 |
| Products | 18 |
| Product categories | 10 |
| Cities | 8 |
| Customer age groups | 4 |
| Dataset columns | 17 |
| Storage formats | CSV and Excel |
| Primary analysis | Descriptive analytics |

### Dataset variables

The report describes the dataset as containing the following types of information:

| Variable | Purpose |
|---|---|
| Order ID | Identifies individual orders |
| Date | Supports daily trend and time-series analysis |
| Order time | Identifies peak ordering hours |
| Product | Identifies the grocery item purchased |
| Category | Supports category-level performance analysis |
| Quantity | Measures the number of units ordered |
| Unit price | Represents the price per unit |
| Discount applied | Captures discounts associated with orders |
| Total order value | Supports revenue and order-value analysis |
| City | Enables geographical comparison |
| Payment mode | Identifies the payment method used |
| Delivery time | Supports delivery performance analysis |
| Customer rating | Measures reported customer satisfaction |
| Order status | Distinguishes delivered and cancelled orders |
| Customer age group | Supports demographic analysis |

The report states that the dataset contains 17 columns. The table above describes the variables explicitly discussed in the report; it is not intended to reconstruct the complete schema or exact column names.

### Data source and reliability

The dataset is simulated because Zepto does not publicly release the user-level order data required for this analysis.

Weighted random sampling was used to model plausible patterns such as:

- Higher demand during evening hours.
- A smaller morning demand peak.
- Increased order volumes on selected weekends and promotional days.
- Greater preference for UPI payments.
- Differences in delivery times and customer ratings across categories.

These assumptions make the dataset suitable for demonstrating analytical methods. However, they do not establish that the same patterns exist in Zepto's actual operations.

---

## 🛠 Tools and Technologies

The project uses the following tools and technologies.

| Technology | Purpose |
|---|---|
| Python | Core programming language for analysis |
| Pandas | Data manipulation, grouping, aggregation, and cleaning |
| NumPy | Synthetic data generation and numerical operations |
| Matplotlib | Charts and graphical visualization |
| Jupyter Notebook | Interactive analysis and documentation |
| CSV | Portable tabular data storage |
| Microsoft Excel | Dataset storage and spreadsheet-based inspection |
| Microsoft Word | Preparation of the final analytical report |
| Git and GitHub | Version control and project sharing |

### Skills demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Descriptive statistics
- Data aggregation and grouping
- Time-based analysis
- KPI calculation
- Data visualization
- Business intelligence and interpretation
- Analytical storytelling
- Translating findings into business recommendations

---

## 🔄 Project Workflow

The project follows a structured analytics workflow.

### Step 1: Data generation

A synthetic dataset was created using Python, NumPy, and Pandas.

The generated records represent grocery orders across products, categories, dates, hours, cities, payment methods, delivery times, and customer ratings.

### Step 2: Data preparation

The dataset was checked for missing values, duplicate order identifiers, inconsistent categorical values, and appropriate date formats.

### Step 3: Data segmentation

Delivered orders were separated from cancelled orders.

Sales and customer-rating analyses were performed on the delivered-order subset unless otherwise stated.

### Step 4: Exploratory data analysis

The prepared dataset was analyzed to understand:

- Product popularity.
- Daily order trends.
- Hourly demand.
- Category ratings.
- On-time delivery performance.
- City-wise engagement.
- Payment method preferences.
- Customer age-group distribution.

### Step 5: KPI calculation

Descriptive measures were calculated, including total revenue, average order value, delivery completion rate, cancellation rate, category ratings, and on-time delivery percentages.

### Step 6: Data visualization

Matplotlib charts were used to present the results in an understandable graphical format.

### Step 7: Business interpretation

The analytical findings were translated into recommendations for inventory management, delivery operations, marketing, and future predictive analytics.

---

## 🧹 Data Cleaning and Preparation

Although the dataset was generated in a structured format, data-quality checks were performed before analysis.

The report documents the following preparation steps:

1. **Missing-value check:** Checked all 17 columns; no missing values were reported.
2. **Duplicate check:** Verified the uniqueness of `Order_ID` and removed duplicate records.
3. **Date conversion:** Converted the `Date` column to a datetime data type for time-series analysis.
4. **Categorical standardization:** Standardized values for Category, City, Payment Mode, and Order Status.
5. **Order-status separation:** Separated cancelled orders from delivered orders for completed-transaction analysis.
6. **Data export:** Exported the prepared dataset to CSV and Excel formats.

### Order-status distribution

| Order status | Orders | Percentage |
|---|---:|---:|
| Delivered | 5,816 | 96.93% |
| Cancelled | 184 | 3.07% |
| **Total** | **6,000** | **100%** |

The delivered-order subset provides the basis for the report's sales and rating analysis, while the overall dataset provides the denominator for the reported order-status percentages.

---

## 📈 Key Performance Indicators (KPIs)

The following metrics summarize the results reported in the analysis.

| KPI | Reported result |
|---|---:|
| Total simulated orders | 6,000 |
| Successfully delivered orders | 5,816 |
| Cancelled orders | 184 |
| Delivery completion rate | 96.93% |
| Cancellation rate | 3.07% |
| Total revenue | ₹6,93,204.65 |
| Average order value | ₹119.19 |
| Average daily order volume | Approximately 194 orders |
| Lowest daily order volume | 145 orders |
| Highest daily order volume | 325 orders |
| Best-selling product | Amul Toned Milk 500ml |
| Units sold for the best-selling product | 1,208 |
| Busiest hour | 9 PM IST |
| Orders recorded at 9 PM | 662 |
| Highest-rated category | Fruits & Vegetables |
| Highest average category rating | 4.47/5 |
| Highest on-time delivery category | Snacks & Munchies |
| Highest category on-time rate | 64.97% |
| Largest city by order volume | Mumbai |
| Mumbai's reported order share | 23.28% |
| Most preferred payment method | UPI |
| UPI's reported order share | 58.75% |

**Interpretation:** The reported results indicate strong simulated order completion, substantial demand for essential grocery products, a pronounced evening ordering peak, and significant variation in on-time delivery performance across categories.

---

## 🔍 Exploratory Data Analysis and Findings

### 1. Most Sold Products

**Business question:** Which products were ordered most frequently during the 30-day period?

The analysis compared product-level unit sales to identify the fastest-moving grocery items.

#### Top five products by units sold

| Rank | Product | Units sold |
|---:|---|---:|
| 1 | Amul Toned Milk 500ml | 1,208 |
| 2 | Banana (Dozen) | 998 |
| 3 | Onion 1kg | 981 |
| 4 | Tomato 1kg | 869 |
| 5 | Farm Fresh Eggs | 866 |

#### Key findings

- Amul Toned Milk 500ml recorded the highest unit sales.
- Bananas and onions also generated substantial demand.
- Milk, fruits, vegetables, and eggs featured prominently among the leading products.
- Products such as Harpic Toilet Cleaner and Pampers Diapers ranked lower in unit sales than the leading essentials.

#### Business implications

The findings suggest that frequently purchased grocery essentials deserve particular attention in inventory planning.

Potential actions include:

- Prioritize replenishment of high-velocity products.
- Improve availability of milk, bananas, onions, tomatoes, and eggs.
- Create convenient reorder shortcuts for frequently purchased items.
- Explore relevant product bundles and repeat-purchase reminders.
- Use complementary-product recommendations to encourage larger baskets.

**Important distinction:** The ranking is based on units sold, not profit margin or revenue by product. A product with fewer units sold could still be more profitable.

---

### 2. Daily Sales and Order-Volume Trend

**Business question:** How did ordering activity change between 1 July and 30 July 2026?

The analysis aggregated orders by date and examined daily fluctuations throughout the month.

#### Key findings

| Metric | Result |
|---|---|
| Average daily orders | Approximately 194 |
| Highest-volume day | 26 July 2026 |
| Orders on the highest-volume day | 325 |
| Lowest-volume day | 15 July 2026 |
| Orders on the lowest-volume day | 145 |

The report identifies additional demand spikes around 6 July and 16 July. It also notes that weekends generally recorded stronger activity than weekdays.

#### Interpretation

Daily order volume was not uniform. The simulated data suggests that promotional events, weekends, and monthly spending patterns may contribute to fluctuations in demand.

The highest-volume day recorded more than twice the number of orders observed on the lowest-volume day.

#### Business implications

- Prepare inventory for expected high-demand dates.
- Schedule delivery partners according to forecast demand.
- Monitor daily order volume to identify sudden increases or decreases.
- Evaluate whether promotions are associated with higher order volume.
- Plan replenishment around expected demand rather than relying exclusively on historical averages.

The reported associations with promotions and payday-related activity are simulation assumptions and interpretations, not independently established causal effects.

---

### 3. Peak Order Hours

**Business question:** At what time of day do customers place the most orders?

Orders were aggregated by hour across the full 30-day period.

#### Reported peak hours

| Hour | Orders |
|---|---:|
| 6 PM | 621 |
| 7 PM | 600 |
| 8 PM | 580 |
| 9 PM | 662 |

The report identifies 9 PM IST as the busiest individual hour, while the broader evening peak occurs between 6 PM and 10 PM.

A smaller morning peak was observed around 8 AM and 9 AM, with 370 and 366 orders, respectively.

#### Key findings

- 9 PM recorded the highest hourly order count.
- Evening hours between 6 PM and 10 PM generated substantial demand.
- Morning orders formed a secondary peak.
- Late-night hours between midnight and 5 AM recorded minimal activity.

#### Business implications

**Evening operations**

- Allocate sufficient picking and packing staff.
- Schedule delivery partners around expected order surges.
- Ensure popular grocery products are available before the evening peak.
- Monitor delivery delays and order backlogs during high-demand periods.

**Morning operations**

- Consider promotions for breakfast essentials.
- Maintain availability of milk, eggs, and other frequently purchased morning products.
- Adjust staffing to match morning demand.

These measures could help improve operational readiness, although actual staffing decisions would require real order and delivery data.

---

### 4. Category Popularity, Customer Ratings, and Delivery Performance

**Business question:** Which product categories receive the highest ratings, and which achieve the strongest on-time delivery performance?

Two complementary measures were evaluated:

1. Average customer rating by category.
2. Percentage of orders delivered within 10 minutes by category.

#### Customer rating results

| Category | Average rating |
|---|---:|
| Fruits & Vegetables | 4.47 |
| Baby Care | 4.47 |
| Dairy & Breakfast | 4.44 |
| Personal Care | 4.40 |
| Snacks & Munchies | 4.39 |
| Home & Cleaning | 4.28 |
| Meat & Seafood | 4.19 |

The report identifies Fruits & Vegetables as the highest-rated category and Meat & Seafood as the lowest-rated category.

The table includes the category values explicitly stated in the report rather than a complete ranking of all ten categories.

#### On-time delivery performance

| Category | On-time delivery percentage |
|---|---:|
| Snacks & Munchies | 64.97% |
| Fruits & Vegetables | 61.78% |
| Beverages | 58.36% |
| Personal Care | 36.74% |
| Home & Cleaning | 27.82% |
| Meat & Seafood | 7.34% |

The report defines on-time delivery as delivery within the 10-minute target.

#### Key findings

- Customer ratings ranged from 4.19 to 4.47.
- On-time delivery performance varied substantially more than customer ratings.
- Snacks & Munchies recorded the highest on-time delivery percentage.
- Fruits & Vegetables combined a high rating with strong on-time performance.
- Meat & Seafood had the lowest reported average rating and on-time delivery percentage.
- Home & Cleaning and Personal Care also recorded comparatively weak delivery performance.

#### Business implications

The findings suggest that customer satisfaction and delivery speed should be evaluated separately.

Potential actions include:

- Investigate picking, packing, and dispatch delays in low-performing categories.
- Review the handling and storage requirements of Meat & Seafood products.
- Evaluate category-specific fulfilment workflows.
- Monitor category-level delivery performance alongside customer ratings.
- Maintain operational practices associated with strong performance in categories such as Snacks & Munchies.

**Important limitation:** The dataset does not establish why delivery performance differs across categories. The report's suggestions concerning product handling, picking time, and fulfilment complexity should be treated as hypotheses to investigate rather than proven causes.

---

### 5. City-Wise Engagement and Payment Preferences

**Business question:** Which cities generate the most orders, and which payment methods are most popular?

The analysis compared order volume across eight cities and calculated payment-mode shares.

#### City-wise order distribution

| City | Orders | Reported share |
|---|---:|---:|
| Mumbai | 1,354 | 23.28% |
| Bengaluru | 1,150 | 19.77% |
| Delhi NCR | 1,050 | 18.05% |
| Pune | Not specified in the report text | 11.78% |
| Hyderabad | Not specified in the report text | 9.11% |
| Chennai | Not specified in the report text | 7.70% |
| Kolkata | Not specified in the report text | 5.93% |
| Ahmedabad | Not specified in the report text | 4.37% |

Mumbai ranked first, followed by Bengaluru and Delhi NCR.

Together, these three cities accounted for approximately 61.10% of the reported city-level order share.

#### Payment-mode preference

| Payment method | Share of orders |
|---|---:|
| UPI | 58.75% |
| Cash on Delivery | 17.26% |
| Credit/Debit Card | 15.35% |
| Wallet | 8.63% |

The displayed payment percentages total approximately 99.99% because of rounding.

#### Customer age-group distribution

| Age group | Reported share of orders |
|---|---:|
| 25–34 | 37.62% |
| 18–24 | 34.70% |
| Other age groups | Not individually specified in the report text |

The two stated age groups together accounted for 72.32% of orders.

#### Key findings

- Mumbai generated the largest share of orders.
- Bengaluru and Delhi NCR were the next-largest city segments.
- UPI was the most popular payment method.
- The reported order distribution was concentrated among customers aged 18–34.

#### Business implications

- Prioritize inventory and operational planning in cities with higher order volumes.
- Investigate growth opportunities in cities with smaller order shares.
- Maintain a convenient and reliable UPI checkout experience.
- Evaluate payment preferences when designing checkout improvements.
- Test customer engagement campaigns for different age groups.

The results describe the simulated dataset only. They do not establish actual city-level market share, population-level customer preferences, or the size of Zepto's real customer base.

---

## 💡 Key Business Insights

The five analyses lead to several broader conclusions.

### 1. Essential products are important demand drivers

Milk, bananas, onions, tomatoes, and eggs ranked among the most frequently purchased products. Inventory planning should account for recurring demand for everyday essentials.

### 2. Demand varies by date and time

Daily order volume and hourly demand fluctuate. Forecasting demand at the appropriate date, hour, and store level could improve inventory and staffing decisions.

### 3. Evening capacity deserves attention

The 6 PM–10 PM period recorded the strongest ordering activity, with 9 PM as the busiest hour. Operational readiness during this period is a clear candidate for further investigation.

### 4. Delivery performance needs category-level monitoring

High customer ratings do not automatically imply high on-time delivery performance. Both measures should be monitored to identify different types of customer-experience issues.

### 5. Customer engagement is geographically concentrated

Mumbai, Bengaluru, and Delhi NCR represented the largest reported city segments. Their simulated demand patterns may help demonstrate how regional analysis can inform inventory and marketing decisions.

### 6. Payment preferences can inform checkout design

UPI accounted for the largest reported payment share. This supports the analytical value of measuring payment-method usage when evaluating the checkout experience.

### 7. Descriptive analytics creates a foundation for prediction

Historical demand patterns, order timing, product preferences, and delivery performance can become input features for future predictive models, provided sufficiently representative real data is available.

---

## 🚀 Business Recommendations

The following recommendations translate the analytical findings into potential business actions.

| Business area | Recommended action | Expected benefit |
|---|---|---|
| Inventory management | Prioritize replenishment of high-volume essentials | Reduce potential stockouts |
| Demand planning | Monitor daily and hourly order patterns | Improve inventory and staffing preparation |
| Delivery operations | Investigate performance during the evening peak | Identify capacity bottlenecks |
| Category management | Investigate low on-time delivery rates | Improve fulfilment reliability |
| Customer experience | Track ratings and delivery performance separately | Identify distinct service issues |
| Marketing | Test relevant promotions and reorder reminders | Encourage repeat purchases |
| Regional strategy | Analyze city-level demand and growth potential | Improve local planning |
| Checkout optimization | Monitor payment-method usage | Support a convenient checkout experience |
| Predictive analytics | Build demand and delivery forecasts using real historical data | Support proactive decisions |

These recommendations are proposed actions, not measured outcomes. Their effectiveness should be evaluated through operational KPIs and controlled experiments.

---

## ▶️ How to Run the Project

The report documents Python-based data generation, cleaning, KPI calculations, and Matplotlib visualization. The commands below provide a reproducible setup for the analysis environment.

### Prerequisites

- Python 3.10 or a compatible Python version.
- Jupyter Notebook or JupyterLab.
- Pandas, NumPy, and Matplotlib.
- The project notebook and the relevant dataset files.

### Step 1: Clone the repository

Replace `YOUR_USERNAME` and `YOUR_REPOSITORY` with your GitHub username and repository name.

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

### Step 2: Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Activate it on macOS or Linux:

```bash
source .venv/bin/activate
```

### Step 3: Install dependencies

```bash
python -m pip install pandas numpy matplotlib jupyter openpyxl
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the project's analysis notebook, if included, and execute the cells in the documented order.

### Step 5: Review the outputs

Depending on the files included in the repository, the analysis may produce:

- Cleaned order-level data.
- Product-level unit-sales summaries.
- Daily order-volume charts.
- Hourly demand charts.
- Category-wise rating comparisons.
- Category-wise on-time delivery comparisons.
- City-wise order summaries.
- Payment-mode distribution charts.
- KPI tables and business insights.

**Reproducibility note:** The commands above set up a compatible environment; they do not guarantee that the project will run until the corresponding notebook, dataset, and analysis code have been included in the repository.

---

## 📁 Suggested GitHub Repository Structure

The following is a recommended structure for organizing the project. It is not a claim about the files already present in the submitted report.

```text
zepto-descriptive-analytics/
│
├── README.md
│
├── data/
│   ├── raw/
│   │   └── synthetic_zepto_orders.csv
│   └── processed/
│       └── cleaned_zepto_orders.csv
│
├── notebooks/
│   └── zepto_descriptive_analytics.ipynb
│
├── src/
│   ├── data_generation.py
│   ├── data_cleaning.py
│   ├── kpi_calculations.py
│   └── visualizations.py
│
├── reports/
│   └── Zepto_Descriptive_Analytics_Report.pdf
│
├── visuals/
│   ├── most_sold_products.png
│   ├── daily_order_trend.png
│   ├── peak_order_hours.png
│   ├── category_ratings.png
│   ├── category_on_time_delivery.png
│   ├── city_wise_orders.png
│   └── payment_mode_distribution.png
│
├── requirements.txt
└── .gitignore
```

### File organization guidelines

- `data/raw/`: Store the generated source dataset.
- `data/processed/`: Store cleaned and analysis-ready data.
- `notebooks/`: Keep exploratory analysis and documented results.
- `src/`: Separate reusable data-processing and analysis functions.
- `reports/`: Store the final analytical report.
- `visuals/`: Store exported charts used in the README and report.
- `requirements.txt`: Document Python dependencies.
- `.gitignore`: Exclude virtual environments, caches, and other unnecessary files.

Because the data is synthetic, sharing a suitably sized dataset may be appropriate. Large files and unnecessary duplicate copies should be avoided.

---

## ⚠️ Limitations

Several limitations should be considered when interpreting the results.

### 1. Synthetic data

The dataset was simulated for academic purposes and is not an official Zepto dataset. The findings cannot establish the company's actual sales, delivery performance, customer demographics, or market position.

### 2. Assumptions embedded in data generation

The generation process intentionally models plausible ordering patterns, including evening peaks and UPI preference. Some observed patterns may therefore reflect the simulation design rather than independently discovered customer behavior.

### 3. Limited analysis period

The dataset covers only 30 days. It cannot reliably establish long-term seasonality, annual trends, or changes across different months and seasons.

### 4. Limited geographical granularity

The report compares eight cities but does not provide a complete operational breakdown at the individual dark-store level.

### 5. Descriptive rather than causal analysis

The analysis identifies patterns and differences but does not prove why those patterns occur. For example, a relationship between promotional dates and higher order volume does not independently establish that promotions caused the increase.

### 6. Limited predictive validation

The report does not demonstrate a trained predictive model, validated forecast accuracy, or measured improvement from an implemented recommendation.

### 7. Delivery metric interpretation

The on-time metric is defined as delivery within 10 minutes. The very low reported rate for Meat & Seafood deserves investigation, but it should not be interpreted as a verified operational failure at Zepto because the underlying dataset is synthetic.

### 8. Profitability is not established

Units sold and total revenue do not establish profitability. The report does not provide a complete cost structure, contribution margins, customer acquisition costs, or category-level profit figures.

These limitations are important when moving from an academic analytics exercise to business decision-making.

---

## 🔮 Future Scope

The project can be extended into more advanced analytics.

### 1. Predictive demand forecasting

Develop forecasting models to estimate future order volume by date, hour, product, and location.

Potential techniques include:

- Time-series forecasting.
- Regression models.
- Tree-based machine learning models.

### 2. Inventory optimization

Estimate the quantities of high-demand products required at different locations and times.

Potential outcomes include reduced stockouts, better replenishment schedules, and lower excess inventory.

### 3. Customer segmentation

Use customer-level historical purchase data to identify distinct behavioral segments, provided suitable real or explicitly simulated customer identifiers and histories are available.

Possible analytical approaches include RFM analysis and clustering.

### 4. Customer churn prediction

Use longitudinal customer activity to identify customers who may stop ordering and evaluate retention strategies.

This would require customer-level historical data that is not established in the current report.

### 5. Delivery-time prediction

Build a model to estimate delivery duration or the probability of missing the 10-minute target.

Potential inputs could include order time, category, order size, distance, picking duration, and rider availability, where those variables are available.

### 6. Recommendation systems

Develop personalized product recommendations using purchase histories, product co-occurrence, and category preferences.

### 7. Statistical hypothesis testing

Test whether observed differences in order volume, category ratings, or delivery performance are statistically meaningful.

### 8. Interactive dashboards

Build an interactive dashboard using Power BI, Tableau, or Streamlit to explore KPIs by date, city, product, category, and hour.

### 9. Real-world validation

Where lawfully available and properly authorized, evaluate the methods using representative real operational data and compare findings against the synthetic baseline.

The future scope should prioritize data quality, validation, and measurable business outcomes rather than model complexity alone.

---

## 🏁 Conclusion

This project demonstrates how descriptive analytics can turn structured grocery order data into interpretable business insights.

The analysis identifies Amul Toned Milk 500ml as the leading product by units sold, 9 PM IST as the busiest ordering hour, Fruits & Vegetables as the highest-rated category, Snacks & Munchies as the category with the highest reported on-time delivery percentage, Mumbai as the largest city segment, and UPI as the most frequently used payment method in the simulated dataset.

The findings also demonstrate the value of monitoring daily demand fluctuations, comparing category-level delivery performance, and examining regional and demographic order distributions.

From a business perspective, these analytical techniques can inform inventory planning, delivery staffing, customer engagement, and operational monitoring. However, the conclusions remain illustrative until validated against representative real-world data.

**Overall, this project establishes a foundation for moving from descriptive analytics toward predictive demand forecasting, customer analytics, and data-driven operational planning.**

---

## 📚 References

The report lists the following references:

1. Zepto — Official quick-commerce platform: https://www.zepto.com
2. Zepto Blog — Product updates and delivery announcements: https://www.zeptonow.com/blog
3. Grand View Research — Online grocery delivery market research: https://www.grandviewresearch.com
4. Statista — Market statistics and consumer research: https://www.statista.com
5. Kaggle — Public datasets and data-analysis resources: https://www.kaggle.com

### Dataset citation

Synthetic Zepto Sales Dataset (30 Days), generated for academic descriptive analytics using simulated order behavior, Indian city-level preferences, and quick-commerce engagement patterns.

These references are listed as provided in the report. The simulated dataset itself is the analytical source for the project's numerical findings.

---

## 👨‍💻 Author

**Your Name**

Data Analytics Project | Descriptive Analytics | Python | Pandas | NumPy | Matplotlib

This project demonstrates practical skills in data preparation, exploratory analysis, KPI development, data visualization, and business insight generation.

### Connect with me

- **GitHub:** https://github.com/YOUR_USERNAME
- **LinkedIn:** https://www.linkedin.com/in/YOUR_PROFILE

Replace the placeholders above with your actual profile links before publishing.

---

## ⭐ Acknowledgment

This project was developed for academic and analytical purposes to demonstrate how descriptive analytics can be applied to grocery ordering behavior.

If you find this project useful, consider giving the repository a star ⭐ and sharing feedback or suggestions for improvement.
 
