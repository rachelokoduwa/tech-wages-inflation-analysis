# Tech Wages vs Inflation vs Income Inequality (2015-2024)

## Overview

There is a common misconception that tech workers made so much money 
after the pandemic that they drove up inflation while everyone else 
suffered. This project pulls real data directly from the Federal Reserve 
(FRED) to find out if that claim actually holds up.

The short answer: it does not. At least not in the way most people think.

## What I Found

Inflation increased year over year after COVID, which is not surprising. 
What was surprising is that the average tech worker was not spared. 
In absolute dollars, tech workers still earn significantly more than 
workers in other sectors. But when you adjust for inflation, tech workers 
actually lost purchasing power just like everyone else.

The most shocking finding was during the peak inflation period of 
2021-2023. Tech wage growth collapsed to around 2.5% while inflation 
was running at nearly 9%. Retail and healthcare workers actually had 
higher wage growth than tech workers during that specific window, 
largely because those workers could not be laid off remotely and had 
more bargaining power.

Professional services workers were the only group that managed to 
stay just above inflation in some periods, which is worth knowing 
if you are considering a career switch purely for financial reasons.

## Why This Matters

This project is useful for anyone trying to understand the real story 
behind wages and inflation:

- **Students** deciding what career path to pursue
- **Working professionals** considering a switch to tech for the money
- **Financial advisors** helping clients understand purchasing power
- **Policy makers** who need to see what the data actually says rather 
  than what the headlines say
- **Anyone** who lived through 2021-2023 and wondered why their 
  paycheck felt smaller even when they got a raise

The data is both sobering and encouraging depending on where you sit. 
Tech workers still earn far more in absolute dollars than any other 
sector. But the idea that they were immune to inflation is simply 
not supported by the numbers.

## Key Visualizations

1. **Average Hourly Wages by Sector (2015-2024)** — shows the absolute 
   dollar gap between tech and other sectors growing over time
2. **Real Purchasing Power Change Post-COVID** — every sector lost 
   purchasing power except professional services which barely broke even
3. **The Pain Period (2021-2023)** — zooms into the peak inflation years 
   and shows tech wage growth actually fell below other sectors
4. **Dollar Gap Between Tech and Other Sectors** — the absolute dollar 
   difference between tech and retail workers grew to $21.60/hr by 2024

## What I Learned About the Data

I initially pulled 10 years of data going back to 2015. After seeing 
the results I went back and narrowed the focus to September 2020 onwards 
because that is when the real tech hiring boom began. Interestingly the 
overall conclusion stayed the same, which was itself a surprising finding. 
The inequality story is not just a post-COVID phenomenon, it has been 
building for a decade.

## Tools Used

- **Python** (Pandas, Matplotlib, Seaborn, Plotly)
- **FRED API** (Federal Reserve Economic Data)
- **GitHub Codespaces** (cloud development environment)

## Data Sources

- Federal Reserve Bank of St. Louis (FRED)
  - CPI: CPIAUCSL
  - Tech & Information wages: CES5500000003
  - Professional Services wages: CES6000000003
  - Healthcare wages: CES6500000003
  - Retail wages: CES4200000003
  - All Workers Average: CES0500000003

## How to Run This Project

1. Clone the repository
2. Open in GitHub Codespaces
3. Create a `.env` file and add your FRED API key:
   `FRED_API_KEY=your_key_here`
4. Get a free API key at fred.stlouisfed.org
5. Open `notebooks/tech_wages_inflation.ipynb`
6. Run all cells from top to bottom

## Author

**Rachel Okoduwa**  


