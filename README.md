## H1N1 & Seasonal Flu Vaccine Prediction

#### Introduction
 This project analyzes the factors influencing seasonal flu vaccine uptake using machine learning. The goal is to build a predictive model that helps public health organizations identify groups that are less likely to get vaccinated, enabling them to design more targeted and effective public health campaigns.

#### Business Problem

The seasonal flu vaccine is one of the most effective strategies for reducing infection and preventing severe illness. However, uptake rates vary across demographic and socioeconomic groups. This project develops a machine learning model to predict whether an individual received the seasonal flu vaccine based on their demographics, health conditions, behaviors, and opinions from the National 2009 H1N1 Flu Survey.

#### Methodology

* Data Source: The dataset comes from the National 2009 H1N1 Flu Survey, containing demographic, behavioral, health-related, and opinion-based information from over 26,000 respondents.

* Data Cleaning: Missing numerical values were imputed with the median, while categorical values were filled with the mode. Pandas was used for data wrangling and preprocessing, including encoding categorical variables and scaling features where needed.

* Key Metric: Model performance was evaluated using ROC AUC as the primary metric, with Precision, Recall, and F1-score also considered to account for class imbalance and minimize false negatives.

* Methodology: The project followed the CRISP-DM framework, including business understanding, data exploration, preparation, modeling (Logistic Regression and Decision Trees), and evaluation. Visualizations (heatmaps, countplots, boxplots) were generated to uncover patterns influencing vaccination uptake.

### Key Findings & Recommendations
1. Targeted Awareness Campaigns: Create health education campaigns specifically aimed at men and younger adults (18–34 years), using social media, influencers, and relatable messaging to stress the importance of flu vaccination. Implement SMS reminders, workplace wellness rewards, or small incentives (like grocery vouchers) to encourage vaccination among low-uptake groups.

2. Community-Based Outreach for Minority Groups and Rural Areas: Partner with Black community leaders, churches, and local organizations to promote flu vaccination and address cultural or historical distrust in healthcare systems.Increase vaccination points in non-metropolitan areas, including partnerships with local pharmacies, churches, and community centers. Use mobile vans and health fairs to reach remote populations.

3. Affordable and Accessible Vaccines for Low-Income & Less-Educated Groups: Provide free or subsidized vaccination clinics in low-income neighborhoods and workplaces. Organize mobile vaccination drives to reach those with transportation or time barriers. Collaborate with schools, adult education centers, and vocational training programs to educate less-educated populations on vaccine benefits using simple, visual, and culturally relevant materials.


### Technologies Used
* Python: The primary programming language.

* Jupyter Notebook, VS Code: For an interactive and step-by-step analysis.

* Pandas: Used for data manipulation and cleaning.

* Scikit-learn: The main machine learning library for model training and evaluation.

* Matplotlib & Seaborn: For data visualization.

### Future Improvements

Use ensemble models (Random Forest, XGBoost) for better accuracy.

Deploy as a web app for real-time prediction and visualization.

### Conclusion
* By adopting this data-driven strategy, public health officials can confidently design targeted vaccination campaigns, improve outreach, and increase overall flu vaccine uptake. The recommendations provide a clear, evidence-based path to boosting vaccination rates and protecting vulnerable populations without requiring broad, one-size-fits-all interventions.


### Presentation 
(https://www.canva.com/design/DAGylv2v1qE/Eg_je7GCQt_m1Ns83oDrLg/edit?utm_content=DAGylv2v1qE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
