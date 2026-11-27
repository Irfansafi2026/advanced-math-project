# Advanced Mathematics Project

## Project Title

The Impact of Diesel Prices on Trucking Fuel Costs in the United States

## University

Vrije Universiteit Brussel (VUB)

## Research Question

How do changes in diesel prices affect trucking fuel costs in the United States?

## Motivation

I am interested in trucking, finance and business management. Understanding fuel costs is important for transportation companies, financial planning and business decision-making.

## Project Objectives

- Analyze historical diesel prices.
- Apply mathematical and statistical methods.
- Estimate monthly trucking fuel costs.
- Create two data visualizations using Python.
- Analyze the financial impact of diesel price changes.

## Data Source

U.S. Energy Information Administration (EIA) via FRED.

https://fred.stlouisfed.org/series/GASDESM

- Period: 2020–2025
- Observations: 72 months
- Unit: US dollars per gallon

## Methodology

The data was imported, filtered and cleaned using Python and Pandas.

Descriptive statistics were calculated, and two graphs were created using Matplotlib.

## Analysis 1: Descriptive Statistics

- Average diesel price: $3.745
- Maximum diesel price: $5.754
- Minimum diesel price: $2.389
- Sample standard deviation: $0.822

[View Diesel Price Graph](diesel_prices.pdf)

## Analysis 2: Fuel Cost Estimation

Assumptions:

- Monthly distance: 10,000 miles
- Fuel efficiency: 6 miles per gallon (MPG)

Formula:

Fuel Cost = (Monthly Miles / MPG) × Diesel Price

Results:

- Average monthly cost: $6,241.97
- Maximum monthly cost: $9,590.00
- Minimum monthly cost: $3,981.67

### Average Monthly Fuel Cost by Year

| Year | Fuel Cost |
|---|---:|
| 2020 | $4,258.75 |
| 2021 | $5,467.64 |
| 2022 | $8,330.28 |
| 2023 | $7,022.78 |
| 2024 | $6,268.75 |
| 2025 | $6,103.61 |

[View Truck Fuel Cost Graph](truck_fuel_costs.pdf)

## Analysis 3: Sensitivity Analysis

This analysis examines the impact of a $1 increase in diesel price per gallon.

- Monthly fuel consumption: 1,666.67 gallons
- Additional monthly fuel cost: $1,666.67
- Additional annual fuel cost: $20,000.00

These results assume that monthly mileage and fuel efficiency remain constant and that the price increase continues for 12 months.

## Business Implications

Monitoring diesel prices can help transportation companies improve budgeting, operating cost management and freight pricing decisions.

## Conclusion

Diesel prices reached their highest level during the studied period in 2022 and declined afterwards.

Higher diesel prices directly increase estimated trucking fuel costs when mileage and fuel efficiency remain constant.

A $1 increase per gallon can increase annual fuel expenses by $20,000 for one truck under the stated assumptions.

## Limitations

The calculated fuel costs are estimates based on fixed mileage and fuel efficiency. They do not represent actual company expenses.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub
- GitHub Pages

## Repository Structure

- GASDESM .csv: Original dataset
- Diesel_Price_Analysis.ipynb: Python analysis
- diesel_prices.pdf: First graph
- truck_fuel_costs.pdf: Second graph
- index.html: Project website
- README.md: Project documentation

## Reproduction

Open the Python notebook in Google Colab and run the code cells in order.

## Project Website

https://irfansafi2026.github.io/advanced-math-project/
