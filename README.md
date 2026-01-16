# Kenya County Poverty & Population Analysis (Excel Project)

**Reported by:** Rita Akumu  
**Tools Used:** Microsoft Excel / Google Sheets  
**Date:** 16 January 2026  
**Scope:** County-level poverty rates (2015/16) with population context (2019)

---

## 📌 Project Overview
This project analyzes poverty rates across Kenya’s 47 counties and compares them against county population and population density.  
The goal is to highlight high-priority counties, estimate the number of people living in poverty, and identify basic patterns that can support policy and development decision-making.

---

## 🎯 Objectives
1. Identify counties with the **highest and lowest poverty rates**
2. Estimate the **number of people living in poverty per county**
3. Compare poverty rate against **population size** and **population density**
4. Summarize insights using charts and a simple **Excel dashboard**

---

## 📂 Data Used
### Key Fields
- **Poverty Rate (%)** — 2015/16  
- **Population** — 2019  
- **Population Density (persons per km²)** — 2019  

### Calculated Fields
- **Estimated People in Poverty** = `Population × Avoided Poverty Rate (%)`
- **Poverty Band**: Low / Medium / High / Very High

---

## 🛠️ Workflow (Excel / Google Sheets)
- Imported poverty and population datasets
- Standardized county names for consistency
- Merged datasets using **County** as the key identifier
- Created calculated columns and summary KPIs
- Built visualizations:
  - Bar charts (top & bottom counties)
  - Histogram (poverty distribution)
  - Scatter plot (poverty vs density)
- Designed a simple dashboard for quick insights

---

## 📊 Key Results (KPIs)
- **Counties analyzed:** 47  
- **Average poverty rate:** 35.4%  
- **Median poverty rate:** 32.8%  
- **Lowest poverty rate:** 15.5%  
- **Highest poverty rate:** 66.1%  
- **Total population (2019):** 47,564,296  
- **Estimated people in poverty (approx.):** 15,288,758  

### Correlation Insights
| Comparison | Correlation |
|----------|-------------|
| Poverty rate vs density | **-0.305** |
| Poverty rate vs population | **-0.368** |

✅ **Interpretation:** Counties with higher population density generally show lower poverty rates, but density alone does not fully explain poverty differences.

---

## 🔍 Key Findings
### Highest Poverty Rate Counties (Top 5)
Counties with the highest poverty rates are mainly in arid and semi-arid areas where access to services and economic opportunities is limited.

- Turkana (66.1%)
- Mandera (61.9%)
- Samburu (60.1%)
- Busia (59.5%)
- West Pokot (57.3%)

### Lowest Poverty Rate Counties (Bottom 5)
Counties with the lowest poverty rates include Nairobi and several counties in central Kenya.

- Nyeri (15.5%)
- Meru (15.5%)
- Nairobi (16.1%)
- Kirinyaga (18.8%)
- Nakuru (19.6%)

### Counties With the Most People in Poverty (Estimated)
High-population counties contribute a large number of people in poverty even if the poverty rate is not the highest.

Top counties by estimated people in poverty:
- Nairobi (~707,929)
- Kilifi (~703,633)
- Kakamega (~621,904)
- Turkana (~612,731)

✅ **Insight:** Nairobi has a relatively low poverty rate but still has a high number of people living in poverty due to its large population.

### Poverty Rate vs Population Density
A scatter plot shows a generally negative relationship:  
**higher density → lower poverty rate**, likely reflecting stronger urban economies and better access to services.  
However, exceptions exist.

---

## ✅ Recommendations
1. Counties with **very high poverty rates** should be prioritized for targeted social support programs.
2. High-population counties with many people in poverty require **scalable interventions**, including an urban poverty focus.
3. Future studies should include variables such as:
   - education levels
   - healthcare access
   - employment
   - infrastructure
   - climat
