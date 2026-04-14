# Role of Climate-Smart Agriculture (CSA) in Addressing Food Security and Climate Change in Nigeria  
### Food Price Stabilisation and Farmers’ Perception (GHS-Panel Wave 5)

---

## 📑 Table of Contents
1. [Project Overview](#project-overview)  
2. [Data Source & Methodology](#data-source--methodology)  
3. [Key Definitions](#key-definitions)  
4. [Tools](#tools)  
5. [Research Objectives](#research-objectives)  
6. [Results](#results)  
7. [Econometric Findings (Regression Output)](#econometric-findings-regression-output)  
8. [Interpretation of Key Results](#interpretation-of-key-results)  
9. [Results Dashboards & Visuals](#results-dashboards--visuals)  
10. [Key Findings & Insights](#key-findings--insights)  
11. [Recommendations](#recommendations)  
12. [Limitations](#limitations)  
13. [Summary](#summary)

---

## Project Overview
Smallholder agriculture in Nigeria is increasingly affected by climate shocks such as droughts, floods, and irregular rainfall.  

This project evaluates the role of **Climate-Smart Agriculture (CSA)** in:
- Food price stabilisation  
- Climate risk perception  
- Climate-related agricultural damages  
- Household resilience outcomes  

The analysis is based on a **weighted sample of 29.51 million respondents** from the **GHS-Panel Wave 5 (2023/2024)**.

---

## Data Source & Methodology
- **Dataset:** GHS-Panel Wave 5 (Post-Harvest Community Questionnaire, Nigeria)  
- **Sample:** Weighted national dataset (n = 29.51 million)  
- **Methods:**  
  - Descriptive statistics  
  - OLS regression  
  - Policy impact interpretation  
  - Data visualisation (Power BI + Python)

---

## Key Definitions

### Climate-Smart Agriculture (CSA)
CSA adoption is defined in the dataset as **households implementing at least one of the following practices**:
- Improved crop varieties (drought/heat resistant)
- Soil conservation practices
- Water management / irrigation techniques
- Agroforestry practices
- Adjusted planting calendars
- Integrated pest management

> ⚠️ Note: “100% adoption” reflects that **at least one CSA practice is present in all sampled households**, not full adoption of all CSA technologies.

---

### Food Price Variable (Important Clarification)
Food price refers to:
> **Community-level average reported food prices (composite indicator across key staple crops)**  

This is not a single crop price, but a **standardised community food price measure**.

---

## Tools
- Excel → data gathering, cleaning, and validation
- Power BI → dashboards and spatial visualisation  
- Python → regression, distributions, and statistical analysis  
  - Pandas  
  - Statsmodels  
  - Matplotlib / Seaborn  

---

## Research Objectives
1. Profile socioeconomic characteristics of farming households  
2. Analyse climate change perceptions  
3. Assess CSA adoption patterns  
4. Evaluate CSA impact on food prices  
5. Examine CSA effectiveness in reducing climate-related damages  

---

## Results

### Objective 1: Socioeconomic Profile
- Male-headed households: **66.32%**  
- Rural population: **72.15%**  
- Primary education: **25.35%**  
- Mean age: **52.19 years**  
- Dominant region: North West (**38.52%**)  

**Insight:** Farming systems are dominated by rural, middle-aged, and low-formal-education households.

---

### Objective 2: Climate Perception
- 70.12% rely on past experience for climate expectations  
- Main expected shocks:
  - Drought (29.26%)  
  - Late rainfall (27.59%)  
  - Flooding (24.71%)  
- Perceived control is low:
  - 42.29% report little control  

**Insight:** Climate adaptation decisions are largely experience-driven rather than forecast-driven.

---

## Econometric Findings (Regression Output)

| Relationship | Coefficient | p-value | Interpretation |
|--------------|-------------|----------|----------------|
| CSA → Food Prices | -29.48 | <0.001 | CSA adoption is associated with lower community food prices (price stabilisation effect) |
| CSA → Damage Score | 0.0629 | <0.001 | Positive association between CSA and reported damages |

---

### ⚠️ Model Metadata (Not Recomputed)
- R²: Not available  
- Standard errors: Not extracted  
- Controls: Household demographics, region, climate exposure variables (as originally specified in model)  
- Sample size: Weighted national dataset (29.51M)

---

## Interpretation of Key Results

### 1. Food Price Stabilisation Effect
CSA adoption is associated with a **₦29.48 reduction in community food prices**, suggesting:
- Improved production stability  
- Reduced supply volatility  
- Enhanced resilience in local food systems  

---

### 2. The “Damage Paradox” 
The positive CSA → damage relationship does NOT necessarily imply CSA increases harm.

Plausible explanations:
- **Higher awareness bias:** CSA users report damages more accurately  
- **Endogeneity effect:** Farmers adopt CSA *because* they already face high climate risk  
- **Exposure concentration:** CSA adoption is higher in high-risk zones  
- **Partial adaptation:** CSA reduces impact severity but not exposure

> 🔍 This is the most analytically important finding and requires subgroup analysis (future work).

---

## Results Dashboards & Visuals
---
### ArcGIS Visualisations

- Geospatial distribution of respondents highlights regions with higher CSA adoption and climate risk perception.  

<details>
<summary>Click to expand ArcGIS visualisations</summary>
<img src="Screenshot%20(935).png" width="700">
</details>
---

### Power BI Dashboards

- Interactive dashboards showing socioeconomic indicators, CSA adoption, and regional food price trends.  

<details>
<summary>Click to expand Power BI visualisations</summary>
<img src="Screenshot%20(931).png" width="700">
<img src="Screenshot%20(932).png" width="700">
<img src="Screenshot%20(933).png" width="700">
</details>
---

### Python Visualisations

- Scatter plots, regression lines, and distribution histograms illustrating CSA adoption, food prices, and climate damage scores.  

<details>
<summary>Click to expand Python Visualisations</summary>
<img src="Screenshot%20(938).png" width="700">
<img src="Screenshot%20(939).png" width="700">
<img src="Screenshot%20(937).png" width="700">
</details>

---

## Key Findings & Insights
- CSA adoption is universal at the “at least one practice” level  
- CSA is linked to **food price stabilisation**  
- Climate perception is experience-driven, not forecast-driven  
- The damage relationship suggests **risk-targeted adoption bias**  
- Regional inequality strongly shapes outcomes  

---

## Recommendations

### High Priority (Evidence-Driven)
- Scale region-specific CSA packages  
- Improve early warning systems  
- Promote drought/flood-resistant varieties  
- Strengthen farmer climate information access  
- Investigate CSA adoption in high-risk zones  

### Medium Priority
- Climate education programs  
- Weather-index insurance expansion  
- Community-level adaptation groups  

---

## Limitations
- Regression not re-estimated  
- Some model diagnostics (R², SE) unavailable  
- CSA variable is binary (limits intensity measurement)  
- Food price index is aggregated at community level  

---

## Summary
CSA shows measurable benefits in stabilising food prices and improving resilience perception, but its relationship with reported damages suggests **complex, non-linear adaptation dynamics** that require deeper subgroup analysis.

---

✍️ Lauren Akhidenor







