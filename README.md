# ACC102_Track2_US_Car_Company_Finance

## 1. Problem & User
This project analyzes the operating performance and financial strength of five major U.S. automakers in recent years (2020-2024) to provide clear, data-driven insights for car buyers and auto enthusiasts.It focuses on key metrics including revenue, net income, profit margin, ROA, and long-term debt ratio to help car buyers and car enthusiasts evaluate brand stability, profitability, and sustainability. The Python-based workflow includes data extraction, cleaning, ratio calculation, and visual comparison, providing clear, data-driven insights for better vehicle purchase decisions.

## 2. Data Source
- Platform: WRDS Compustat
- Access date: April 11, 2026
- Period: 2020–2024 (most recent 5 years)
- Companies: Ford(F), GM(GM), Tesla(TSLA), Rivian(RIVN), Lucid(LCID)

## 3. Python Methods
- WRDS connection & SQL query
- Data cleaning: drop missing values
- Financial ratios: profit margin, ROA, debt-to-equity
- Bar charts for comparison

## 4. Key Findings
- Traditional firms (Ford, GM) have stable high revenue.
- Tesla leads in profitability and efficiency.
- EV startups (Rivian, Lucid) show low or negative margins.
- Financial strength reflects brand stability for car buyers.

## 5. Demo Video


## 6. How to Run
pip install wrds pandas matplotlib numpy

## 7. Limitations
- Only annual data used
- No macroeconomic factors included
- Future: add quarterly data & cash flow analysis
