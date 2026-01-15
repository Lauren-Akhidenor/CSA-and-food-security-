# Role of Climate-Smart Agriculture (CSA) in Addressing Food Security and Climate Change in Nigeria: Food Price Stabilisation and Farmers’ Perception

---

## 📑 Table of Contents
1. [Project Overview](#project-overview)
2. [Data Source & Methodology](#data-source-and-methodology)
3. [Tools](#tools)
4. [Research Objectives](#research-objectives)
5. [Results](#results)
6. [Results Dashboards & Visuals](#results-dashboards-and-visuals)
7. [Key Findings & Insights](#key-findings-and-insights)
8. [Recommendations by Priority](#recommendations-by-priority)
9. [Summary](#summary)


---

## Project Overview
Smallholder agriculture in Nigeria faces increasing climate risks, including floods, droughts, and erratic rainfall, threatening food security and household incomes. Climate-Smart Agriculture (CSA) offers adaptive strategies, yet adoption patterns, socioeconomic drivers, and impact on food prices remain underexplored.  

This project evaluates: socioeconomic characteristics, climate perceptions, CSA adoption, links to food price stabilisation, and effects on climate-related damages. Analysis is based on a **weighted sample of 29.51 million respondents** from the **GHS-Panel Wave 5 (2023/2024)**.

Descriptive statistics, regression, and data visualisation were used to assess relationships between CSA practices, economic outcomes, and climate resilience.

---

## Data Source & Methodology
- **Dataset:** GHS-Panel Wave 5 (2023/2024), Post-Harvest Community Questionnaire (Nigeria)  
- **Sample:** Excel-based random selection to obtain a representative sub-sample (weighted n = 29.51 million)  
- **Variables:** CSA adoption practices, community food prices, climate expectations, damages, and household characteristics  
- **Methodology:** Descriptive statistics | Ordinary Least Squares (OLS) regression | Development impact evaluation | Data visualisation for policy insight  

---

## Tools 
- **Power BI** – Dashboards and interactive visualisation of socioeconomic and CSA indicators  
- **Python** – Pandas, Statsmodels, Matplotlib, Seaborn for regression, trend and distribution analyses  

---

## Research Objectives
1. Describe the socioeconomic characteristics of agricultural households in Nigeria.  
2. Examine farmers’ perceptions and expectations of climate change.  
3. Assess the level and patterns of CSA adoption.  
4. Analyse the relationship between CSA adoption and food prices.  
5. Evaluate CSA’s effectiveness in mitigating climate-related damages.

---

## Results

### Objective 1: Socioeconomic Characteristics
- Predominantly male households (**66.32%**)  
- Majority rural (**72.15%**)  
- Education mainly primary (**25.35%**)  
- Most respondents in North West zone (**38.52%**)  
- Mean age: 52.19 years  

**Insight:** Households are largely rural, middle-aged, and have limited formal education, influencing adoption of climate-smart practices.

### Objective 2: Perceptions and Expectations
- 70.12% rely on **past experience** to anticipate climate events  
- Frequency of expected events: sometimes (51.34%), rarely (32.42%), often (7.26%), every year (8.77%)  
- Expected events: drought (29.26%), late rains (27.59%), flooding (24.71%)  
- Expected damages: crops (15.43%) and livestock (15.18%)  
- Perceived control: low to moderate (42.29% little control)  

**Insight:** Farmers have limited perceived control over climate risks and expect increasing event frequency.

### Objective 3–5: CSA Adoption & Econometric Analysis
- **CSA adoption:** 100% of households implemented at least one CSA practice  

**OLS Regression Findings:**

| Relationship        | Coefficient | p-value  | Interpretation |
|--------------------|-------------|----------|----------------|
| CSA → Food Prices   | -29.48      | <0.001   | CSA adoption is associated with **lower food prices**, indicating stabilisation effects. |
| CSA → Damage Score  | 0.0629      | <0.001   | CSA adoption linked to slightly higher reported damages, likely due to **greater awareness or partial protection**. |

---

## Results Dashboards & Visuals

### ArcGIS Visualisations
- Geospatial distribution of respondents highlights regions with higher CSA adoption and climate risk perception.  

<details>
<summary>Click to expand ArcGIS visualisations</summary>
<img src="Screenshot%20(935).png" width="700">
</details>

### Power BI Dashboards
- Interactive dashboards showing socioeconomic indicators, CSA adoption, and regional food price trends.  

<details>
<summary>Click to expand Power BI visualisations</summary>
<img src="Screenshot%20(931).png" width="700">
<img src="Screenshot%20(932).png" width="700">
<img src="Screenshot%20(933).png" width="700">
</details>

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

**CSA reduces food prices by ₦29.48 per unit** 

**Statistical significance:** p < 0.001 

- This demonstrates that CSA adoption has **measurable economic benefits** for smallholders and consumers alike.
- CSA is widely adopted, yet effectiveness varies regionally.  
- CSA adoption contributes to **food price stabilisation** but does not fully mitigate climate damages.  
- Economic and spatial analyses reveal **regional disparities** in adoption, perception, and resilience.  
- Findings support **evidence-based policy, programme design, and impact evaluation**.


---

## Recommendations by Priority

| Priority | Top Recommendations |
|----------|-------------------|
| **High** | Prioritize high-impact CSA practices; region-specific packages; upgrade early warning systems; localized climate advisories; investigate CSA-damage paradox; drought/flood-resistant varieties; livestock protection; build farmer self-efficacy; target female-headed households; scale proven practices; CSA-linked credit; develop a national CSA framework |
| **Medium** | Community climate intermediaries; farmer adaptation committees; age-appropriate training; weather-indexed insurance |

---

## Summary: 
High-priority actions focus on **direct CSA implementation, scaling, and credit linkage**, while medium-priority actions strengthen **community structures and capacity-building**.  
Together, these interventions support **climate resilience, food security, and inclusive agricultural development**.

---

