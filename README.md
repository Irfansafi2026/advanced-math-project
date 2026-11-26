# Advanced Mathematics Project

## Research Question

How do changes in diesel prices affect trucking fuel costs in the United States?

## Motivation

I am interested in trucking, finance and business management.

## Data Source

U.S. Energy Information Administration via FRED.

https://fred.stlouisfed.org/series/GASDESM

Period: 2020-2025.

Observations: 72 months.

## Analysis 1: Descriptive Statistics

- Average price: $3.745

- Maximum price: $5.754

- Minimum price: $2.389

- Sample standard deviation: $0.822

## Analysis 2: Fuel Cost Estimation

Assumptions: 10,000 miles per month and 6 miles per gallon.

Formula: Fuel Cost = (Miles / MPG) * Diesel Price

- Average monthly cost: $6,241.97

- Maximum monthly cost: $9,590.00

- Minimum monthly cost: $3,981.67

## Conclusion

Diesel prices peaked in 2022 and declined afterwards. Higher diesel prices increase estimated trucking fuel costs.

The costs are estimates, not actual company expenses.

## Repository Structure

- GASDESM .csv: Original dataset

- Diesel_Price_Analysis.ipynb: Python code

- diesel_prices.pdf: First graph

- truck_fuel_costs.pdf: Second graph

- index.html: Website

- README.md: Documentation

## Reproduction

Open the notebook in Google Colab and run the code cells in order.

## Project Website

https://irfansafi2026.github.io/advanced-math-project/
