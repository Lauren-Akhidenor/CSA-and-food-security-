````markdown
# 🌍 Role of Climate-Smart Agriculture (CSA) in Addressing Challenges of Food Security and Climate Change in Nigeria through Food Price Stabilization and Farmers’ Perception

## 📘 Project Overview

Agriculture in Nigeria is increasingly threatened by climate change, with smallholder farmers facing rising incidences of floods, droughts, and erratic rainfall. These changes disrupt food production systems and pose a serious threat to national food security. While Climate-Smart Agriculture (CSA) is promoted as a key adaptive strategy, there is limited empirical evidence on its adoption, effectiveness, and the factors influencing its uptake across different regions of Nigeria. Furthermore, farmers’ perceptions and expectations of climate risks remain understudied, particularly in relation to food price stabilization and reported climate-related damages.

This study aimed to:

1. Describe the socioeconomic characteristics of agricultural households.
2. Assess the perception and expectation of climate change.
3. Measure CSA adoption levels among agricultural households.
4. Analyse the relationship between CSA adoption and food prices.
5. Evaluate the influence of CSA practices on climate-related damage experiences.

The research utilized nationally representative secondary data from the General Household Survey (GHS-Panel Wave 5, 2023/2024). Due to the enormous dataset size, **Excel-based random sampling** was employed to generate a representative sub-sample. This procedure ensured analytical feasibility while maintaining the representativeness of the national population, resulting in a weighted analysis of **29.51 million respondents**.

Both descriptive statistics and regression models were employed to assess relationships between key variables such as CSA scores (CSA_SCORE), sector, gender, food prices, and climate damages.

Key findings revealed that most respondents were male, resided in rural areas, and had relatively low levels of formal education. Perceptions and expectations of climate change were largely based on past agricultural experiences, with droughts, late onset of rains, and flooding being the most anticipated events. Over 70% of respondents reported CSA scores above average, indicating widespread adoption of climate-adaptive practices. Regression analysis showed that CSA adoption was significantly associated with **lower food prices**, but also with **higher reporting of climate damages**, likely reflecting increased awareness and sensitivity among adopters.

The study recommends expanding CSA awareness programs, strengthening adaptive infrastructure in rural zones, enhancing early warning systems, and addressing gender and regional disparities in agricultural policy and interventions.

---

## 📊 Data Source & Methodology

- **Dataset:** GHS-Panel Wave 5 (2023/2024) – Post-Harvest Community Questionnaire (Nigeria).
- **Sampling Method:** Excel-based random sampling was used to extract a representative sub-sample due to the large dataset size. The analysis reflects a **weighted population of 29.51 million respondents**.
- **Variables Included:**
  - CSA adoption practices (soil conservation, irrigation, improved seeds, etc.)
  - Community food prices
  - Climate event expectations and damages
  - Socioeconomic characteristics
- **Regression Model:** Ordinary Least Squares (OLS) regression was applied using **Python’s Statsmodels** package.

---

## 🛠️ Tools
- **Python** (Pandas, Statsmodels, Matplotlib, Seaborn)
- **Power BI** (visual storytelling and dashboards)

---

## 🎯 Research Objectives
- Describe the socioeconomic characteristics of agricultural households in Nigeria.
- Identify the perception of climate change and expectations among agricultural households in Nigeria.
- Examine the extent of adoption of Climate-Smart Agriculture (CSA) practices among agricultural households in Nigeria.
- Analyse the relationship between CSA adoption and food prices in Nigeria.
- Evaluate the effectiveness of CSA practices in reducing climate-related damages to agricultural production.

---

## 📊 Results

### Objective 1: Socioeconomic Characteristics of Agricultural Households
The analysis covered **29.51 million respondents** (weighted) derived from Excel-based random sampling. The dataset was cleaned using post-harvest community documentation to ensure reliability.

- **Sex:** Majority were **male (66.32%)**.
- **Sector:** **72.15%** resided in rural areas.
- **Education:** **Primary education** accounted for the highest share (**25.35%**).
- **Regional Distribution:** **North West zone** had the highest share (**38.52%**).
- **Age:** Largest group was **38–47 years (23.72%)**. Mean age = **52.19 years**, min = 18, max = 90.

These findings show Nigerian agricultural households are largely rural, middle-aged, and characterized by low levels of formal education.

### Objective 2: Perceptions and Expectations of Climate Change
Key results include:
- **Reasons for Expectation:** **70.12%** based expectations on past agricultural experiences.
- **Frequency of Occurrence:** **51.34% sometimes**, **32.42% rarely**, **7.26% often**, **8.77% every year**.
- **Expected Events:** **Drought (29.26%)**, **late onset of rains (27.59%)**, **flooding (24.71%)**.
- **Damage Expectation:** Highest for **crop losses (15.43%)** and **livestock losses (15.18%)**.
- **Perceived Control:** **42.29% little control**, **23.03% some control**, **20.79% no control**.
- **Review:** **49.68% increased**, **27.38% same**, **22.94% decreased**.

### Objective 3–5: CSA Adoption and Econometric Analysis
- **CSA Adoption Rate:** 100% of communities adopted at least one CSA practice.
- **Regression Results (OLS):**
  - **CSA → Food Prices:** Coef = **-29.48 (p < 0.001)** → Higher CSA adoption is linked to **lower food prices**, showing CSA’s role in **food price stabilization**.
  - **CSA → Damage Score:** Coef = **0.0629 (p < 0.001)** → Higher CSA adoption is linked to **slightly higher reporting of climate damages**, possibly due to increased awareness or incomplete protection.

---

## 🔍 Insights
- CSA practices are universally adopted, but their **effectiveness varies**.
- CSA contributes to **price stability**, supporting food security.
- CSA does **not fully mitigate damages**, indicating implementation gaps.

---

## 🚀 How to Run
```bash
git clone https://github.com/your-username/CSA-FoodSecurity-Analysis.git
cd CSA-FoodSecurity-Analysis
pip install -r requirements.txt
````

```
```
