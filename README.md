# ENIAC Discount Strategy Analysis — A Data Science Story

This repository contains the second **collaborative project** from our **Data Science & AI course at WBS Coding School**. Our goal: analyze ENIAC's discount strategy from 2017-2018 and provide data-driven recommendations to optimize revenue while maintaining brand positioning.

## 📖 Summary

This project was more than Python scripts and Seaborn plots — it was about uncovering the **story hidden in messy real-world data**.

We started with **four separate CSV files** containing orders, products, brands, and transaction details from ENIAC's 437-day operational period. The data was far from clean — inconsistent formats, duplicates, missing values, and mismatched records that reflected the reality of business data systems.

Through systematic **data cleaning and exploration**, we discovered patterns in customer behavior, seasonal trends, and the true impact of discount strategies on revenue generation.

Our analysis revealed that ENIAC was already succeeding with discounts — **€7.82M in revenue supported by €1.39M in strategic discount investment** — but there was room for optimization.

**Our conclusion:** ENIAC should implement a three-pronged approach focusing on the 11-20% discount sweet spot during major holidays while protecting premium brand positioning.

## 🛠 Languages and Tools Used

- **Python & Pandas** → Data cleaning and manipulation
- **Seaborn & Matplotlib** → Data visualization and pattern discovery  
- **Google Colab** → Collaborative analysis environment
- **Jupyter Notebooks** → Interactive data exploration
- **Google Slides** → Team presentation and storytelling
- **Apple Keynote** → Final presentation with animation

## 📊 Key Data Insights

**The Numbers That Told the Story:**
- **437 days** of transaction data (January 2017 - March 2018)
- **40,985 completed orders** across **5,098 products** from **177 brands**  
- **€7.82M total revenue** generated with **€1.39M discount investment**
- **Storage products dominated** with 36.0% of revenue (€2.81M)
- **Q4 2017 seasonal peak** drove €3.04M in revenue alone

**The Sweet Spot Discovery:**
Our analysis revealed that **11-20% discounts during strategic periods** produced the optimal balance between customer attraction and profitability. Higher discounts (30%+) drove more orders but significantly reduced overall revenue.

## 🎯 Sample Visualizations

The visualizations in this project tell the complete business story:

**Seasonal Revenue Patterns**
- Clear Q4 peaks showing Christmas season driving €2.3M+ monthly revenue
- Distinct holiday periods: Easter, Summer sales, and Christmas holidays
- Monthly order volume correlation with revenue trends

**Discount Performance Analysis**  
- Revenue vs discount percentage showing the 11-20% optimization zone
- Product category breakdown revealing Storage and Mobile dominance
- Seasonal discount timing aligned with peak customer expectations

**Business Impact Charts**
- ROI visualization demonstrating discount investment effectiveness
- Brand protection analysis for premium products (Apple)
- Three-year strategic recommendation framework

## 🎓 Key Learnings

**Data Quality is Everything**
The most significant learning was that **data cleaning consumed 60%+ of our project time**. Real business data is messy — inconsistent formats, duplicate records, missing values, and logical inconsistencies that don't exist in textbook examples.

**Visual Exploration Accelerates Insights**  
Creating plots early in the analysis process helped us ask better questions and identify patterns we would have missed in pure numerical analysis. Graphs became our roadmap for deeper investigation.

**Business Context Drives Technical Decisions**
Understanding ENIAC's position as a premium tech retailer shaped every analytical choice — from how we handled outliers to which discount ranges we prioritized in our recommendations.

**Collaborative Analysis Strengthens Results**
Working as a team meant multiple perspectives on the same data, catching errors, and building more robust conclusions than any individual analysis could achieve.

## ⚡ Challenges Overcome

**The Messy Data Reality**
- **Inconsistent data formats** across four different CSV files
- **Missing product information** requiring strategic imputation decisions  
- **Duplicate records** with subtle differences requiring careful deduplication
- **Date format variations** that broke initial analysis attempts

**Balancing Depth with Clarity**
Learning to present complex analytical findings to a business audience meant focusing on actionable insights rather than technical methodology. The "CEO presentation" format pushed us to translate data science into business strategy.

**Team Coordination in Data Science**
Unlike our previous SQL project, this Python analysis required coordinating Jupyter notebooks, shared data processing decisions, and merged analytical conclusions across team members.

## 💡 Personal Reflections

This project reinforced that **data science is fundamentally about problem-solving, not just programming**. The technical skills — Python, Pandas, Seaborn — were tools in service of understanding business challenges.

**The 60/40 rule became real:** 60% data cleaning and preparation, 40% analysis and insight generation. This ratio taught me to respect the unglamorous but critical foundation work that enables reliable conclusions.

**Presenting to business stakeholders** required a different mindset than academic analysis. Every visualization needed to answer "So what?" and every recommendation needed to connect directly to revenue impact.

The transition from exploring data to making strategic recommendations showed me how data science bridges technical analysis with business decision-making.

## 📂 Repository Structure

```
eniac-discount-strategy-analysis/
├── README.md                          # This story
├── data/
│   ├── raw/                          # Original messy CSV files
│   │   ├── brands.csv
│   │   ├── orders_qu.csv
│   │   ├── products_cl.csv
│   │   └── orderlines_qu.csv
│   └── cleaned/                      # Processed and joined data
│       └── orderlines_qu.csv
|       └── orders_qu.csv
|       └── products_qu.csv
|       └── revenue_per_orders.csv
|       └── orders_avg_diff_paid_no_outliers.csv 
├── notebooks/                        # Our analytical journey
│   ├── 01_data_cleaning_with_pandas_solutions.ipynb
│   ├── 02_quality_assessment_solution.ipynb
│   └── 03_category_creation_solution.ipynb
|   └── 4_joinning_products_orders_orderlines.ipynb
|   └── 5_main_analysis.ipynb
|   └── Vennel_exploration.ipynb 
├── visualizations/ exploratory plots    # The charts that told the story
│   ├── discount_revenue_orders.png
│   ├── revenue_per_category.png
│   └── discount_revenue_time.png
├── presentation/                     # Final business presentation
│   └── ENIAC_Discount_Strategy_Analysis.pdf
└── requirements.txt                  # Python dependencies
```

## 🚀 Strategic Recommendations Delivered

**Three-Pronged "Right Time, Right Products" Strategy:**

1. **Sweet Spot for Big Events** — Deploy 11-20% discounts exclusively during Black Friday, Christmas, and major holidays when customers expect deeper discounts

2. **Protect Premium Brand** — Maintain 0-10% discounts for Apple premium products to preserve ENIAC's positioning as a trusted premium tech reseller  

3. **Test and Learn** — Implement controlled testing with yearly assessments to adapt to changing customer landscapes

## 🎯 Project Context

**WBS Coding School Data Science & AI Bootcamp**
**Team Project** | **Business Analysis Focus** | **Real-World Data Application**

This analysis bridges the gap between data science education and business application, demonstrating how systematic data exploration can generate actionable strategic recommendations for revenue optimization.

