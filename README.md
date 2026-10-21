# 🇰🇪 DataSprint 2026: Predicting Financial Deterioration Among Kenyan Adults

**Team Name:** Team Gen

## 👥 Team Members

- Angel Mugo - Statistics and Data science (Group Leader) 
- Kathryn Bii - Financial Economics
- Mukabwa Gloria - Informatics and Computer Science

## 📌 Project Overview

This project was developed for the **DataSprint 2026 challenge** using data from the 2024 FinAccess Household Survey. The objective was to develop a machine learning model capable of predicting whether a Kenyan adult's financial situation had **improved, stayed the same, or worsened** compared to the previous year.

The project explores the factors associated with financial deterioration in Kenya and demonstrates how machine learning can support evidence-based decision-making. The findings can inform policymakers, financial institutions, NGOs, and development partners seeking to identify financially vulnerable populations and design targeted interventions that strengthen financial inclusion and resilience.

## 📊 Dataset

| Attribute | Description |
|---|---|
| Data Source | 2024 FinAccess Household Survey |
| Number of Records | 20,871 respondents |
| Geographic Coverage | All 47 counties in Kenya |
| Problem Type | Multiclass Classification |
| Target Variable | Change in financial situation |

### Target Classes

The model predicts one of three possible outcomes:

- **Improved:** The respondent's financial situation improved compared to the previous year.
- **Stayed the Same:** The respondent's financial situation remained relatively unchanged.
- **Worsened:** The respondent's financial situation deteriorated compared to the previous year.

## 🛠️ Tools and Technologies

The project used the following tools and libraries:

- **Python** — Programming language
- **Jupyter Notebook** — Interactive analysis and experimentation
- **Pandas & NumPy** — Data manipulation and numerical computing
- **Matplotlib** — Data visualization
- **Scikit-learn** — Machine learning, preprocessing, and model evaluation
- **XGBoost** — Gradient boosting model development and optimization
- **SMOTE** — Experiments with techniques for addressing class imbalance

## 🔬 Methodology

The project followed a structured machine learning workflow:

1. **Data Loading and Exploration:** Loaded the survey dataset and examined its structure, variables, and distributions.
2. **Data Cleaning and Preprocessing:** Prepared the dataset for analysis and modelling.
3. **Exploratory Data Analysis (EDA):** Investigated financial outcomes and relationships between respondent characteristics and financial deterioration.
4. **Feature Engineering:** Prepared relevant features for machine learning.
5. **Model Development:** Trained and evaluated multiple classification models.
6. **Model Evaluation:** Compared model performance using the weighted F1 score, taking class imbalance into consideration.
7. **Model Optimization:** Tuned the XGBoost model to improve predictive performance.
8. **Interpretation and Recommendations:** Examined feature importance and translated the findings into practical recommendations.

## 🔎 Key Findings

The analysis highlighted several factors associated with financial outcomes among Kenyan adults:

- **Financial deterioration:** More than half of respondents reported that their financial situation had worsened.
- **Emergency financial preparedness:** Access to emergency funds emerged as one of the strongest predictors of financial outcomes.
- **Digital financial inclusion:** Access to mobile money and digital financial services was an important factor in understanding financial resilience.
- **Structural vulnerabilities:** Factors such as lower education levels, food insecurity, and debt stress were associated with financial deterioration.
- **Financial literacy:** Financial literacy alone showed limited predictive power in the model, highlighting the importance of considering it alongside access to financial products and services.

## 📈 Model Performance

The final tuned **XGBoost classifier** achieved a weighted F1 score of approximately **0.52**.

The model demonstrated particularly strong recall in identifying respondents whose financial situations had worsened.

The weighted F1 score accounts for the relative frequency of each class, making it useful for evaluating classification performance when the target classes are imbalanced.

*Note: Model performance should be interpreted in the context of the dataset, target distribution, evaluation methodology, and the limitations of survey-based prediction.*

## 💡 Recommendations

Based on the findings, the project proposes the following recommendations:

1. **Strengthen emergency savings:** Promote accessible financial products that help households build emergency funds and withstand unexpected expenses.
2. **Expand digital financial inclusion:** Improve access to digital financial services and address barriers to mobile money usage.
3. **Connect financial literacy with practical services:** Complement financial education with access to savings accounts, suitable credit products, and other financial services.
4. **Support financially vulnerable populations:** Use data-driven insights to inform targeted interventions for groups facing financial insecurity.
5. **Encourage evidence-based policymaking:** Apply survey analytics and predictive modelling to support the development of financial inclusion and resilience initiatives.

## 📁 Repository Contents

The repository contains the following project files:

```text
DataSprint-2026/
├── DataSprint_2026_Team_Gen.ipynb
├── DataSprint2026_Presentation.pptx
├── visuals/
│   ├── chart_1.png
│   └── ...
└── README.md
```

- **`DataSprint_2026_Team_Gen.ipynb`** — Main Jupyter Notebook containing the data analysis, feature engineering, model development, and evaluation.
- **`DataSprint2026_Presentation.pptx`** — Seven-slide presentation summarizing the project, findings, and recommendations.
- **`visuals/`** — Exported charts and figures illustrating the analysis.
- **`README.md`** — Project documentation and overview.

## 🎯 Project Impact

This project demonstrates how machine learning can be applied to survey data to investigate financial vulnerability and identify factors associated with changes in household financial well-being.

By combining exploratory data analysis, predictive modelling, model evaluation, and interpretation, the project illustrates the potential for data-driven approaches to contribute to financial inclusion research and policy discussions in Kenya.

## 🙏 Acknowledgements

This project was completed as part of the **DataSprint 2026 challenge**, using data from the **2024 FinAccess Household Survey**.

Special thanks to the organizations and individuals involved in producing the survey data that makes research into financial inclusion and resilience possible.
