Gaming Laptops 2026 Q1 - Discount & Brand Analysis (EDA)

---- Project Overview
This project performs an exploratory data analysis (EDA) on a Kaggle dataset of a current, high-performance laptop market capturing real-time pricing, consumer ratings and detailed hardware descriptions for over 600 modern gaming rigs. The goal is to understand brand-level discount strategies and examine relationships between price, discounts, customer reviews and ratings.

---- Key Questions
1. Which gaming laptop brands offered the highest average discounts?
2. How consistent are discounts across different brands?
3. Is there a relationship between:
    a. Price and customer ratings?
    b. Review volume and ratings?
    c. Discouunt percentage and perceived quality?

---- Dataset
Source: path = kagglehub.dataset_download("kanchana1990/gaming-laptops-2026")
Key columns:
- 'brand'
- 'price'
- 'discount_pct'
- 'reviews_count'
- 'stars'

---- Tools and Libraries
- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

---- Analysis Steps
1. Data loading and inspection
2. Brand-level discount aggregation
3. Discount distribution analysis using boxplots
4. Correlation matrix between numerical features
5. Scatter plots for deeper relationship analysis

---- Key insights
- Some brands consistently offer high average discounts, indicating aggressive pricing strategies
- higher-priced laptops tend to receive larger discounts
- heavily discounted laptops often do not have the highest ratings

--- IMPROVEMENTS
- Add price bands (budget, mid-range, premium)
- Build interactive PBI dashboard
- Track discount trends over time

######

Author
Gillian F
Aspiring Data Analyst | Python in VS Code | Power BI | Excel
