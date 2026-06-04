# 🏦 Saudi Banking Credit Intelligence Dashboard

> An interactive Power BI dashboard analyzing **28 years of Saudi banking data** across economic sectors, residential mortgages, and consumer lending — powered by official data from the Saudi Central Bank (SAMA).

![dashboard](Saudi-banking-credit-dashboard/screenshots/Screenshot 2026-06-04 100423.png)
![dashboard](Saudi-banking-credit-dashboard/screenshots/Screenshot 2026-06-04 100451.png)
![dashboard](Saudi-banking-credit-dashboard/screenshots/Screenshot 2026-06-04 100528.png)
![dashboard](Saudi-banking-credit-dashboard/screenshots/Screenshot 2026-06-04 100552.png)

---

## 📊 Project Overview

This interactive Power BI dashboard provides a comprehensive analysis of Saudi Arabia's banking credit landscape, examining three key dimensions of bank lending using official data from the Saudi Central Bank (SAMA):

- **Economic Activity Lending** (2021–2025): How banks distribute credit across 17 economic sectors
- **Residential Mortgages** (2018–2025): The transformation of Saudi housing finance
- **Consumer Lending Behavior** (1998–2025): 28 years of consumer credit evolution

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** — Dashboard development and visualization
- **Power Query (M Language)** — Data extraction, cleaning, and unpivoting
- **DAX (Data Analysis Expressions)** — Calculated measures, time intelligence, and dynamic insights
- **Microsoft Excel** — Initial data preparation

### Key Technical Implementations

✅ **Star Schema Data Model** — Centralized Date dimension connecting three fact tables
✅ **20+ DAX Measures** — Including time intelligence (YoY growth, peak detection)
✅ **Dynamic Insights** — Auto-updating text based on user filters
✅ **Smart Unit Formatting** — Automatic conversion between Millions/Billions/Trillions SAR
✅ **Multi-period Analysis** — Each page uses its optimal date range
✅ **Page-level Filtering** — Honest handling of varying data availability

---

## 📥 Data Source

**Source:** [Saudi Central Bank (SAMA) — Monthly Statistical Bulletin](https://www.sama.gov.sa/en-US/Publications/EconomicReports/Pages/report.aspx?cid=55)

**Categories Analyzed:**
1. **Bank Credit Classified By Economic Activity** — 17 economic sectors (ISIC4 classification)
2. **Residential New Mortgages Finance For Individuals** — Houses, Apartments, Land
3. **Consumer and Credit Card Loans** — Detailed consumer lending categories

**Data Specifications:**
- **Currency:** Saudi Riyals (SAR), in Millions
- **Frequency:** Annual data
- **Coverage:** Varies by category (see below)

| Category | Period | Years |
|----------|--------|-------|
| Economic Activity | 2021–2025 | 5 |
| Mortgages | 2018–2025 | 8 |
| Consumer Loans | 1998–2025 | 28 |

---

## 📸 Dashboard Pages

### Page 1: Landing Page
Project introduction with navigation to detailed analysis pages.

### Page 2: Economic Activity Analysis (2021–2025)
- Total bank credit trends across 17 economic sectors
- Sector ranking and market share
- Year-over-year growth analysis
- Top performing sector identification

### Page 3: Mortgage Market Analysis (2018–2025)
- Residential financing trends over Vision 2030 era
- Property type distribution (Houses, Apartments, Land)
- Mortgage market boom-and-correction story
- Dynamic insights with property type dominance

### Page 4: Consumer Lending Behavior (1998–2025)
- **28-year consumer credit evolution** — the longest dataset
- Historical events impact (2008 crisis, 2015 oil crash, 2020 COVID)
- Detailed category breakdown (2016+)
- Vision 2030 era acceleration analysis

---

## 🔍 Key Insights Discovered

### Economic Activity (2021–2025)
- **60% growth** in total bank credit over 5 years
- **Individuals' Loans** dominate at 47% of total credit
- **Real Estate Activities** ranks #2, reflecting housing sector strength
- Vision 2030 priority sectors show accelerated lending

### Mortgages (2018–2025)
- **189.9% total growth** from 2018 to 2025
- **Houses dominate** at 66% of total financing
- Peak years: **2020–2021** during Sakani program acceleration
- Market correction observed post-2021 (interest rate impact)

### Consumer Loans (1998–2025)
- **978% growth** over 28 years
- **Renovation & Home Improvement** leads detailed categories since 2016
- Visible impact of 2008 financial crisis, 2015 oil price drop, and 2020 COVID
- Strong recovery and acceleration during Vision 2030 era (2016+)

---

## 💡 Methodology Notes

### Handling Data Limitations

A key challenge in this project was that SAMA's detailed consumer loan categorization only began in 2016. Rather than misrepresenting the data, the dashboard transparently splits the Consumer Loans page into two sections:

- **Top section (1998–2025):** Total consumer credit trend over 28 years
- **Bottom section (2016–2025):** Detailed category breakdown with disclaimer

This approach preserves both the long-term growth narrative and the granular category insights while maintaining data integrity.

### Smart Unit Formatting

Source data is in Millions SAR. To improve readability without losing accuracy, the dashboard uses DAX measures to dynamically format values:

- Values under 1,000 Million → "X Million SAR"
- Values 1,000–1,000,000 Million → "X.X Billion SAR"
- Values over 1,000,000 Million → "X.X Trillion SAR"

---

**Connect with me:**
- 📧 Email: Bedooralmareni@gmail.com
- 🔗 LinkedIn: [Bedoor Alsulami](https://www.linkedin.com/in/bedoor-alsulami)

---

**Data Attribution:** All data sourced from the Saudi Central Bank (SAMA). This project is for educational and portfolio purposes only. Original data remains the property of SAMA.

---

## 🙏 Acknowledgments

- **Saudi Central Bank (SAMA)** for providing comprehensive public financial data
- **Microsoft Power BI Community** for tutorials, forums, and inspiration

---

*Last updated: June 2026*
