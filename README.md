## H1N1 & Seasonal Flu Vaccine Prediction

#### Introduction
This project analyzes the factors influencing seasonal flu vaccine uptake using machine learning. The goal is to build a predictive model that helps public health organizations identify groups that are less likely to get vaccinated, enabling them to design more targeted and effective public health campaigns.

#### Project Overview

This project uses the National 2009 H1N1 Flu Survey dataset to predict whether individuals received the seasonal flu vaccine. The dataset contains demographic, behavioral, and opinion-based features that influence vaccination uptake.

The goal is to help public health officials identify groups less likely to vaccinate and design targeted interventions to improve vaccine adoption.

#### Methodology

The project follows the CRISP-DM framework:

Business Understanding → Define the problem and objectives.

Data Understanding → Explore dataset, handle missing values, and visualize patterns.

Data Preparation → Clean data, encode categorical variables, scale features, and split data.

Modeling → Train and evaluate classification models:

Logistic Regression (baseline, interpretable)

Decision Tree (captures non-linear patterns)

Evaluation → Metrics used include ROC AUC, Precision, Recall, and F1-score.

Deployment (Future Work) → Model can be integrated into a dashboard for health policy decision-making.

### Key Features Used

Medical: chronic conditions, health worker status, doctor recommendations.

Opinions: perceived effectiveness, flu risk, concerns about side effects.

Demographics: age group, education, income, race, marital status, employment, household structure.

Behaviors: handwashing, mask use, avoiding crowds, etc.


#### Technologies Used
Python: The primary programming language.

Jupyter Notebook: For an interactive and step-by-step analysis.

Pandas: Used for data manipulation and cleaning.

Scikit-learn: The main machine learning library for model training and evaluation.

Matplotlib & Seaborn: For data visualization.

### Results

Logistic Regression outperformed Decision Tree in generalization with higher ROC AUC (~0.76).

Vaccination uptake strongly associated with:

Doctor recommendations

Positive opinions about vaccine effectiveness

Higher education & income levels



### Contributors

Group 11 (Phase 3 Project Members)

### Future Improvements

Use ensemble models (Random Forest, XGBoost) for better accuracy.

Deploy as a web app for real-time prediction and visualization.
### Presentation 
(https://www.canva.com/design/DAGylv2v1qE/Eg_je7GCQt_m1Ns83oDrLg/edit?utm_content=DAGylv2v1qE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
