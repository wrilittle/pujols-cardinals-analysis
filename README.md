# Albert Pujols: Decline in Production with the Angels

## 📌 Project Overview
This project analyzes Albert Pujols’s offensive performance after leaving the St. Louis Cardinals (2001–2011) and signing with the Los Angeles Angels (2012–2021).  
The goal is to demonstrate how aging, injuries, and role changes can be quantified using modern baseball metrics.

This is a **sports analytics case study** designed to showcase skills in:
- Data collection and cleaning
- Exploratory data analysis (EDA) with Python (pandas, matplotlib)
- Advanced sabermetrics (wRC+, WAR, OPS)
- Communicating insights with data visualization

---

## ❓ Research Question
> How did Albert Pujols’s production change after leaving the Cardinals, and what factors contributed to the decline?

---

## 📊 Data Sources
- [Baseball Reference](https://www.baseball-reference.com/players/p/pujolal01.shtml)  
- [FanGraphs](https://www.fangraphs.com/players/albert-pujols/1015/stats?position=1B)  

Collected CSVs of yearly batting stats from 2001–2021.

---

## 🔎 Methodology
1. Split career into two segments:  
   - **St. Louis Cardinals (2001–2011)**  
   - **Los Angeles Angels (2012–2021)**  

2. Calculated key metrics:
   - Weighted Runs Created Plus (wRC+)
   - Batting Average (AVG)
   - Wins Above Replacement (WAR)   
   - On-Base Percentage (OBP)  
   - Slugging (SLG)  
   - OPS 

3. Created visualizations to highlight year-over-year changes.  

---

## 📈 Key Findings
- **Cardinals (2001–2011):** .328 AVG, 167 wRC+ (elite production, 67% above league average).  
- **Angels (2012–2021):** .256 AVG, 108 wRC+ (slightly above average, significant decline).  
- The drop correlates with:
  - **Age curve:** contract started at age 32.  
  - **Chronic foot/leg injuries:** multiple surgeries limited mobility.  
  - **Loss of bat speed:** reduced ability to drive pitches.  

---

## 🧠 Takeaways
- Even Hall of Fame hitters experience sharp regression when athletic decline and injuries compound.  
- Long-term contracts for players past 30 often carry high risk.  
- This type of analysis can be extended to other players/contracts to evaluate decision-making in roster construction.

---

## 🚀 Next Steps
- Build aging curve comparisons for other first basemen (e.g., Cabrera, Thome).  
- Expand to Wins Above Replacement (WAR) trendlines.  
- Develop a simple model predicting production decline based on age/injury history.
- Continue use of wRC+ because of value and impact 
---
