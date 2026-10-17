# Global Content Strategy Analysis (Netflix)

An exploratory data analysis (EDA) project evaluating Netflix’s global media catalog to generate data-driven content production and regional growth strategies for business stakeholders.

---

## 📊 Project Overview
Netflix hosts over 10,000 titles and serves over 222 million subscribers globally. This project analyzes a comprehensive dataset of Netflix movies and TV shows to understand content distribution across countries, historical release patterns, format preferences (Movies vs. TV Shows), and key drivers for international expansion. 

The primary objective is to translate technical exploratory data findings into clear, jargon-free business recommendations for executive leadership.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Cleaning:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab

---

## 🔍 Key Analysis Steps
1. **Data Inspection & Pre-processing:** 
   * Assessed data shapes, data types, and handled missing values across attributes like `director`, `cast`, `country`, and `date_added`.
   * Performed text unnesting for multi-valued categorical columns (`country`, `director`, `cast`) to ensure accurate group-level statistics.
2. **Non-Graphical Analysis:**
   * Generated value counts, frequency distributions, and unique attribute summaries.
3. **Visual Analysis (Univariate & Bivariate):**
   * Plotted distributions for continuous and categorical variables using histograms, count plots, box plots, and distplots to evaluate content growth over the last 20–30 years.
   * Examined regional content variations and the shifting strategic balance between Movies and TV Shows in recent years.
4. **Outlier & Missing Value Evaluation:**
   * Inspected dataset gaps and analyzed the distribution range of release years and durations.

---

## 💡 Key Business Insights
* **Catalog Shift:** While movies historically dominate the platform's volume, recent years show a strategic acceleration in TV Show additions to drive user retention.
* **Geographic Hubs:** Content production is heavily concentrated in top-tier markets (such as the US and India), highlighting substantial whitespace opportunities for localized regional content production in underserved international territories.
* **Release Timing & Growth:** Significant scaling in content additions post-2015 aligns with Netflix's aggressive international expansion phase.

---

## 🚀 Strategic Recommendations
* **Diversify Regional Production:** Invest heavily in localized non-English content production hubs outside North America to capture emerging international subscriber bases.
* **Optimize Content Mix:** Balance movie acquisitions with serialized TV show investments to maximize platform engagement and customer lifetime value.
* **Targeted Release Windows:** Tailor release timing and genre allocations based on regional preferences uncovered via unnested country-genre analytics.

---
