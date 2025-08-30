# Role of Climate-Smart Agriculture (CSA) in Addressing Challenges of Food Security and Climate Change in Nigeria through Food Price Stabilization and Farmers’ Perception

## 📑 Table of Contents
1. [Project Overview](#-project-overview)
2. [Data Source & Methodology](#-data-source--methodology)
3. [Tools](#-tools)
5. [Research Objectives](#-research-objectives)
6. [Results](#-results)
   - [Objective 1: Socioeconomic Characteristics](#objective-1-socioeconomic-characteristics-of-agricultural-households)
   - [Objective 2: Perceptions and Expectations](#objective-2-perceptions-and-expectations-of-climate-change)
   - [Objective 3–5: CSA Adoption & Regression Analysis](#objective-35-csa-adoption-and-econometric-analysis)
7. [Results Dashboards & Visuals](#-results-dashboards--visuals)
   - [ArcGIS Visualizations](#arcgis-visualizations)
   - [Power BI Dashboards](#power-bi-dashboards)
   - [Python Visualizations](#python-visualizations)
9. [Insights](#-insights)
10. [How to Run](#-how-to-run)
11. [Contributing](#-contributing)


---

## Project Overview
Agriculture in Nigeria is increasingly threatened by climate change, with smallholder farmers facing rising incidences of floods, droughts, and erratic rainfall. These disruptions to food production systems pose a serious threat to national food security. Climate-Smart Agriculture (CSA) is promoted as a key adaptive strategy, but little is known about its adoption, effectiveness, and the socioeconomic and regional factors influencing it. Farmers’ perceptions and expectations of climate risks also remain underexplored, especially concerning food price stabilization and climate-related damages.

This project investigates:
1. The socioeconomic characteristics of agricultural households.
2. Perceptions and expectations of climate change.
3. Adoption levels of CSA practices.
4. The relationship between CSA adoption and food prices.
5. The influence of CSA practices on climate-related damage experiences.

The research draws from the **General Household Survey (GHS-Panel Wave 5, 2023/2024)**. Due to the enormous dataset, **Excel-based random sampling** was employed to extract a manageable sub-sample, maintaining representativeness. This yielded a **weighted analysis of 29.51 million respondents**.

Descriptive statistics and **OLS regression models** (using Python’s Statsmodels) were applied to examine links between CSA scores, food prices, and climate damages.

---

## Data Source & Methodology
- **Dataset:** GHS-Panel Wave 5 (2023/2024) Post-Harvest Community Questionnaire (Nigeria).
- **Sampling Method:** Excel-based random sampling for manageable analysis; results reflect a **weighted 29.51 million respondents**.
- **Variables Included:**
  - CSA adoption practices (soil conservation, irrigation, improved seeds, etc.)
  - Community food prices
  - Climate event expectations and damages
  - Socioeconomic characteristics
- **Model:** Ordinary Least Squares (OLS) regression.

---

## Tools
- **ArcGIS in Power BI** (geospatial mapping of respondents across Nigeria)
- **Power BI** (dashboards for perception and socioeconomic visualization)
- **Python** (Pandas, Statsmodels, Matplotlib, Seaborn)
  


---

## Research Objectives
- Describe the socioeconomic characteristics of agricultural households in Nigeria.
- Identify the perception of climate change and expectations among agricultural households in Nigeria.
- Examine the extent of CSA adoption among agricultural households in Nigeria.
- Analyse the relationship between CSA adoption and food prices in Nigeria.
- Evaluate the effectiveness of CSA in reducing climate-related damages to agricultural production.

---

## Results

### Objective 1: Socioeconomic Characteristics of Agricultural Households
- **Sex:** Majority male (**66.32%**).
- **Sector:** **72.15%** rural.
- **Education:** **Primary education** highest share (**25.35%**).
- **Region:** **North West zone** dominant (**38.52%**).
- **Age:** Largest group 38–47 years (**23.72%**). Mean = 52.19 years (min 18, max 90).

➡️ Nigerian agricultural households are largely rural, middle-aged, and have low formal education.

### Objective 2: Perceptions and Expectations of Climate Change
- **Reason for Expectation:** **70.12%** based on past experiences.
- **Frequency:** **51.34% sometimes**, **32.42% rarely**, **7.26% often**, **8.77% every year**.
- **Expected Events:** Drought (**29.26%**), late rains (**27.59%**), flooding (**24.71%**).
- **Expected Damages:** Crops (**15.43%**) and livestock (**15.18%**).
- **Control Perception:** 42.29% little control, 23.03% some control, 20.79% no control.
- **Trend:** 49.68% perceive increase, 27.38% same, 22.94% decrease.

➡️ Farmers rely heavily on lived experience, expect more frequent events, and perceive limited ability to control climate damages.

### Objective 3–5: CSA Adoption and Econometric Analysis
- **CSA Adoption Rate:** 100% (all communities adopted at least one CSA practice).

**OLS Regression Results:**

| Relationship        | Coefficient | p-value  | Interpretation |
|---------------------|-------------|----------|----------------|
| CSA → Food Prices   | -29.48      | <0.001   | CSA adoption is linked to **lower food prices**, indicating CSA contributes to **price stabilization**. |
| CSA → Damage Score  | 0.0629      | <0.001   | CSA adoption is linked to **slightly higher reported damages**, possibly due to greater awareness or partial protection. |

---

## Results Dashboards & Visuals

### ArcGIS Visualizations
Geospatial distribution of respondents across Nigeria using **ArcGIS integrated in Power BI**.
- Mapping highlights zones with higher CSA adoption and climate perception variations.
- Visual layers show **regional clustering** of respondents and **zone-specific vulnerabilities**.

### ArcGIS Visualizations
<details>
<summary>Click to expand ArcGIS visualizations</summary>
<img src="Screenshot%20(935).png" width="700">
</details>


### Power BI Dashboards
<details>
<summary>Click to expand Power BI visualizations</summary>

<img src="Screenshot%20(931).png" width="700">
<img src="Screenshot%20(932).png" width="700">
<img src="Screenshot%20(933).png" width="700">
</details>



### Python Visualizations
Python-based plots complement regression results:
- **CSA Adoption vs Food Prices** (scatter and regression line).
- **CSA Adoption vs Climate Damage Score** (distribution plots).
- **CSA Adoption Score Distribution** (histogram/density plots).

  ### Python Visualizations
<details>
<summary>Click to expand Python Visualizations</summary>
<img src="Screenshot%20(938).png" width="700">
<img src="Screenshot%20(939).png" width="700">
<img src="Screenshot%20(937).png" width="700">
</details>

---

## Insights
- CSA is **universally adopted**, but its **effectiveness varies**.
- CSA adoption is associated with **lower food prices**, supporting food security.
- CSA does not fully mitigate damages, showing implementation and adaptation gaps.
- ArcGIS mapping reveals **regional disparities** in CSA adoption and climate perceptions.

---

## How to Run
```bash
git clone https://github.com/Lauren-Akhidenor/CSA-and-food-security-.git
cd CSA-and-food-security-
pip install -r requirements.txt
````

---

## Contributing

Contributions, issues, and feature requests are welcome! Fork the repo and submit a pull request.

---
```
```
