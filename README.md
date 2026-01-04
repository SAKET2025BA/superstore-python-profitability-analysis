# Superstore Sales & Profit Analysis (Python EDA)

## Project Overview

This project examines sales and profitability patterns in the Superstore dataset using Python. The purpose of the analysis is to understand **where and why profit is created or lost**, across product categories, discount levels, and regions, and to reason through these findings from a business decision-making perspective.

## Objectives

- Assess overall sales and profit performance
- Analyze category-level profitability and margin behavior
- Examine the impact of discounting on profit at a granular level
- Identify region-wise profit and loss concentration
- Apply Python (pandas, matplotlib, seaborn) to conduct structured business analysis

## Dataset

- **Source:** Superstore dataset  
- **Format:** CSV  
- **Level:** Order-level transactional data  

### Key Fields

- Sales  
- Profit  
- Discount  
- Category / Sub-Category  
- Region  
- Order Date and Ship Date 

**Note:** The dataset required latin1 encoding due to non-UTF8 characters.

## Tools & Libraries Used

- Python  
- pandas  
- matplotlib
- seaborn
- Jupyter Notebook  

## Project Structure

## Project Structure

├── data/
│   └── superstore.csv
│
├── notebooks/
│   └── Day_19_20_Python_Superstore_Analysis.ipynb
│
└── README.md


## Key Business Insights

- The business generates **strong sales volume (over $2.29M)**, but profitability remains modest in comparison, indicating margin pressure.
- **Technology** consistently performs well and absorbs discounts better than other categories, reflecting healthier unit economics.
- **Furniture** shows structural weakness: high sales but low or negative margins, especially in certain regions.
- The **West region** is the primary contributor to profit, while the **Central region** shows higher loss concentration.
- Importantly, **losses appear even at low discount levels in some categories**, which challenges the assumption that discounting alone causes poor performance.
- Discounts tend to **amplify existing weaknesses** rather than create losses from scratch; category economics and regional dynamics play a larger role.

## Analytical Approach & Visualizations

The analysis follows a clear, step-by-step diagnostic flow:

- Start with overall business KPIs to understand scale and performance
- Break profitability down by category and region
- Examine discount impact using row-level profit margins and discount bands
- Identify where losses concentrate across categories and regions

Visualizations were used selectively, with an emphasis on **clarity over quantity**, to make patterns and risks easy to interpret.


## Conclusion

This project shows that strong revenue does not automatically translate into strong profitability. While discounting does affect margins, it is **not the root cause of losses**. Sustainable improvement requires a more nuanced approach—focusing on **category-specific economics, regional performance, and disciplined pricing decisions**.
The analysis reinforces the importance of looking beyond topline growth and asking harder questions about where and why value is created or lost.


## Author

**Saket Kumar Mallik**  
MBA – Business Analytics  

## Next Steps

- Combine these findings with SQL and Power BI analyses  
- Extend the analysis to customer-level profitability  
- Build a capstone project integrating Python, SQL, Excel, and Power BI  

## How to Run

1. Open the notebook inside the `notebooks/` folder  
2. Ensure the dataset is available in the `data/` folder  
3. Run all cells sequentially