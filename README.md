# Bank Loan Analysis (Python)

A data analysis project exploring bank loan applications, funded amounts, and repayment outcomes using Python, Pandas, Matplotlib, and Plotly.

## Project Overview
This project analyzes a bank loan dataset to understand:
- **Loan quality** (Good vs Bad loans based on loan status)
- **Monthly trends** in funded amount, received amount, and application count
- **Regional patterns** by state
- **Funding distribution** by loan term, employment length, purpose, and home ownership

## Key Metrics (KPIs)
- Total loan applications
- Good loan applications (Fully Paid + Current)
- Good loan funded amount (in $ Millions)
- Good loan total received (in $ Millions)
- Percentage of good loans
- Monthly funded / received amount trends
- Total funded amount by:
  - State
  - Term (36 vs 60 months)
  - Employment length
  - Loan purpose
  - Home ownership

## Visualizations Included
- **Good Loan Metrics** summary
- **Monthly Trends by Issue Date**  
  - Total funded amount by month (area + line)
  - Total received amount by month (area + line)
  - Total loan applications by month (area + line)
- **Regional Analysis by State** (horizontal bar chart)
- **Loan Term Analysis** (donut chart)
- **Employment Length vs Funded Amount** (horizontal bar chart)
- **Loan Purpose vs Funded Amount** (horizontal bar chart)
- **Home Ownership vs Funded Amount** (Plotly treemap)

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- Plotly Express
- Jupyter Notebook
