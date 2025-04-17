# Life_Expectancy_Data_Analysis_Project

## 🔍 Project Overview  
This project analyzes **global life expectancy** trends (2000-2015) using data from the World Health Organization (WHO) Global Health Observatory (GHO). The goal is to uncover key factors influencing life expectancy across different countries and identify actionable insights for public health policy.

## 🎯 Key Objectives
✔ Examine trends in life expectancy across regions and income groups.
✔ Identify correlations between life expectancy and factors like GDP, healthcare spending, and disease prevalence.
✔ Predict life expectancy using regression models (e.g., Linear Regression, Random Forest).
✔ Provide data-driven recommendations for improving global health outcomes.

## 📂 Dataset  
- **Source:** [Kaggle Netflix Dataset](https://drive.google.com/file/d/1NDSLORGfC-gLNlr5LILBw71UmKUjd_HG/view?usp=drive_link) 
- **Features:** 'Country', 'Year', 'Status', 'Life expectancy', 'Adult Mortality', 'infant deaths', 'Alcohol', 'percentage expenditure', 'Hepatitis B', 'Measles', 'BMI', 'under-five deaths', 'Polio', 'Total expenditure', 'Diphtheria', 'HIV/AIDS', 'GDP', 'Population', 'thinness 1-19 years', 'thinness 5-9 years', 'Income composition of resources', 'Schooling'. 

## 🛠️ Tech Stack  
- Python (Pandas, Scikit-learn)  
- EDA & Predictive Modeling  
- Data Visualization (Matplotlib, Seaborn)

 ## 📊 Key Findings
 - Developed countries exhibit significantly higher life expectancy compared to developing nations.
 - The top 10 countries with the highest life expectancy (averaging 81.7–82.5 years) are all developed nations, led by: Japan (82.54 years),Sweden (82.52 years),Iceland (82.44 years) followed by Switzerland, France, Italy, Spain, Australia, Norway, and Canada.
 - The bottom 10 countries for life expectancy (averaging 46.1–51.4 years) are all low-income African nations, with: Sierra Leone (46.1 years) at the lowest, Central African Republic (48.5 years), Lesotho (48.8 years), followed by Angola, Malawi, Chad, Côte d’Ivoire, Zimbabwe, Swaziland (Eswatini), and Nigeria.
 - Analysis reveals a strong positive correlation between childhood immunization rates (diphtheria and polio) and national life expectancy.
 - Analysis reveals a strong positive correlation between childhood immunization rates (diphtheria and polio) and national life expectancy.
 - Wealthier nations (higher GDP per capita) and those with equitable resource distribution consistently exhibit higher life expectancy.
 - A 1.0 increase in HIV/AIDS deaths (per 1,000 live births) corresponds with a ~10-year decline in life expectancy.

## Statistical Analysis Findings
- A highly significant difference exists in life expectancy between high-income and low-income countries (t = 28.32, p < 0.001)
- Countries with higher healthcare expenditures exhibit significantly longer life expectancies than those with lower spending (t = 23.45, p < 0.001)

## Recommendations
- To improve overall life expectancy, we should focus more on developing countries through targeted healthcare investment and economic initiatives to push them toward becoming developed nations.
- If all nations matched Japan’s life expectancy, global averages would rise by ~5 years.Prioritizing preventive care and equitable healthcare access could close 50% of this gap.
- If the bottom 10 nations matched Rwanda’s progress (+10 years in 20 years), 50M+ lives could be saved per decade. This requires a large investment in targeted health aid.
- Closing the immunization gap in the 10 worst-performing nations could prevent more than 1M child deaths/year, adding ~5 years to their average life expectancy within a decades.
- A dual focus on education (especially for women) and equitable resource distribution could close the life expectancy gap between developed and developing nations.
- Eliminating mother-to-child HIV transmission in high-burden countries could increase national life expectancy.

## 💻 How to Run  
1. Clone repo: `git clone [repo-link]`    
2. Run Jupyter Notebook: [`life_expectancy_analysis.ipynb`](https://drive.google.com/file/d/1RTIP6UGkRRMTy-9Ap7CyJQF9h0Abyfqr/view?usp=drive_link)














