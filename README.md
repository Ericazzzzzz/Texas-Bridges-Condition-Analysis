# 🛠️ Texas Bridges Condition Analysis

**🔍 Project Overview**:  
This project investigates the condition of bridges across Texas using data science techniques. By analyzing data from the National Bridge Inspection database, we aim to predict bridge conditions and support maintenance planning through a regression-based predictive model. 

---

**📌 Key Steps**:

1. **Data Preparation**:
  - Processed and cleaned complex bridge data, focusing on essential features like age, traffic volume, material, and design to streamline analysis.
  - Combined condition scores (`Deck_rating`, `Superstr_rating`, and `Substr_rating`) into a single target variable for regression analysis, allowing a continuous rating for bridge health.
   - Analyzed and handled outliers in continuous variables, ensuring they reflected plausible bridge conditions rather than data errors.

2. **Exploratory Data Analysis**:
   - Explored relationships between predictor variables (e.g., `Age`, `AverageDaily`, `Trucks_percent`, `Material`, `Design`) and the bridge condition target variable.
   - Visualized interactions between continuous and categorical predictors, highlighting key patterns in how different variables relate to bridge conditions.
   - Assessed the relationships among predictors to avoid multicollinearity, providing preliminary insights into their individual and combined influence on bridge condition.

3. **Regression Modeling**:
  - Developed and evaluated two linear regression models; Model 1 used continuous predictors while Model 2 added categorical predicors.
  - Evaluated each model performance and compared predictor influences to find the most impactful predictor to the bridges condition.

---

**🚀 Results**:
- The regression models successfully highlighted age as an important influential factors in bridge condition and after incorporating categorical variables, age and materials are the key predictors for predicting the Texas bridges condition.
- Analyzed residuals, finding an approximately normal distribution centred around zero, with residuals within -5 to +5, indicating reasonable accuracy in predictions.
- Suggested exploring non-linear models and additional predictors (e.g., climate, geology, and maintenance history) to enhance model accuracy beyond the limitations of linear regression.

---

**🛠️ Technologies**:  
Python, Pandas, Scikit-Learn, Matplotlib, Seaborn

---

🔗 [Check the full project on GitHub]([https://github.com/Ericazzzzzz/Texas-Bridges-Condition-Analysis])
