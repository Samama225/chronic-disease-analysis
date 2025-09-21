# U.S. Chronic Disease Analysis (COPD & Obesity)

This project analyzes the **U.S. Chronic Disease Indicators dataset** (from data.gov/CDC) to explore, visualize, and model trends in **Chronic Obstructive Pulmonary Disease (COPD)** and **Obesity**.  
The goal is to extract insights for **public health policy** and provide **individual recommendations** for prevention.

---

## 📊 Project Workflow

### 1. Data Cleaning
- Handled missing values (median imputation for numeric, constant fill for categorical).
- Converted `DataValue` to numeric for analysis.
- Dropped columns with >80% missing values.

### 2. Exploratory Data Analysis
- Distribution of indicators across states & years.
- Identified **COPD** and **Obesity** as focus diseases for deeper analysis.

### 3. Choropleth Maps
- Created **state-level prevalence maps** to visualize geographic hotspots.
- Useful for public health officials to see where interventions are most needed.

### 4. Trends Over Time
- Analyzed **yearly trends** in COPD and Obesity prevalence.
- Compared both diseases side-by-side to highlight long-term shifts.

### 5. Predictive Modeling
- Built a **RandomForest Classifier** with median-split target (high vs. low prevalence).
- Evaluated performance with accuracy & ROC-AUC.
- Extracted **feature importances** to identify major drivers of disease prevalence.

### 6. Interpretability
- Used SHAP (if available) for model explanation.
- Highlighted which factors contribute most to disease burden.

### 7. Recommendations
**Policy Level**
- Target high-prevalence states with more resources (prevention campaigns, healthcare access).
- Monitor trends yearly to adjust strategies.

**Individual Level**
- Promote smoking cessation programs (COPD prevention).
- Encourage healthy diet & physical activity (Obesity prevention).
- Regular screening in high-risk populations.

---

📈 Key Insights

Obesity prevalence is rising faster than COPD in many regions.

Geographic hotspots show clear disparities (some states consistently higher).

Models highlight lifestyle and demographic factors as major drivers.


🧑‍⚕️ Impact

This project goes beyond modeling by tying data insights back to public health action.
It shows how data science + healthcare can work together to shape better prevention strategies.




