# Strategic Player Valuation and Performance Forecasting in Franchise Cricket (IPL)

## 📌 Project Overview
Franchise sports leagues operate as highly lucrative financial ecosystems constrained by strict salary caps. During player auctions, teams often suffer from the "Winner's Curse," overpaying for marquee players based on basic aggregate statistics while ignoring situational performance. 

This project diagnoses the Indian Premier League (IPL) financial ecosystem to identify actionable market inefficiencies. By merging 17 years of on-field performance metrics, franchise financial records, and macroeconomic factors, this analysis evaluates the true, inflation-adjusted cost of purchasing a run to maximize franchise ROI.

## 🛠️ Tech Stack & Tools
* **Data Wrangling & Cleaning:** Python (Pandas, Regular Expressions)
* **Data Visualization & BI:** Tableau (Interactive Dashboards, Dual-Axis Charts, Calculated Fields)
* **Analytical Concepts:** Feature Engineering, Relational Data Modeling, Macroeconomic Integration (CPI)

## 📊 Interactive Dashboards
https://public.tableau.com/app/profile/swayam.patel31

*(Tableau dashboard: `Dashboard 1`)* <img width="1505" height="900" alt="image" src="https://github.com/user-attachments/assets/129ec214-cdf8-47af-a035-2da3a1fde9e6" />
*(Tableau dashboard: `Dashboard 2`)* <img width="1500" height="888" alt="image" src="https://github.com/user-attachments/assets/318148d8-0246-4a1e-8555-37949af63e81" />


## 🧠 Key Strategic Insights
1. **Top-Order Visibility Commands the Highest Premium:** The auction market heavily favors Opening Batters (averaging ₹6.02 Cr), while offering high-leverage value for Pure Specialists like Middle-Order Batters (₹2.44 Cr) at a steep discount.
2. **Run Inflation is Driven by Volume, Not Reckless Risk:** Average team scores have exploded from the 140s to over 186 runs, yet wicket-loss rates remain perfectly static.
3. **Run Efficiency Outpaces Currency Expansion:** Contrary to the belief that auction prices are inflated, an inflation-adjusted correlation of -0.90 reveals that the "real cost" of production has decreased significantly over time. Modern franchises are securing substantially higher on-field efficiency per rupee spent compared to early league seasons

## ⚙️ Data Architecture & Wrangling Challenges
* Engineered a multi-dimensional relational model to clean and standardize over **255,000 granular, ball-by-ball delivery records**.
* Developed a custom Python parsing pipeline utilizing Regex to systematically strip currency symbols and apply mathematical multipliers to text-heavy financial ledgers.
* Standardized 17 years of historical franchise data to account for rebranded teams while retaining defunct franchises to preserve the integrity of all-time statistical leaderboards.

## 📂 Full Documentation
For a deep dive into the methodology and mathematical calculations, please review the attached documentation:
* [Executive Datafolio](./Datafolio_Swayam_Patel.pdf)
* [Comprehensive Final Report](./Final_Report_Swayam_Patel.pdf)
