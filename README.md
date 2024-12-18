# Smart Promotion: AI-Driven Employee Evaluation
# Yizhang Yang

This project aims to improve efficiency and reliability of promotion decisions of an organization by analyzing employee data from last year's promotion cycle. Explanatory Data Analysis and Machine Learning modelling are performed to identify key factors of promotions and make promotion predictions based on these factors. Insights from both EDA and ML models are aligned to make recommendations for future promotion-relevant practices.

- **Techniques Used**
    - Univariate analysis with descriptive statistics and histogram
    - Bivariate analysis with pearson and spearman correlation heatmap
    - Categorical analysis with faceted bar plots
    - Training, fine-tuning and evaluation of XGBoost and Random Forest with GridSearch CV, classification report and ROC-AUC score
    - Explanainable AI with SHAP plots.

- **Key Findings**
    - Good performance metrics(training scores and ratings) can significantly improve promotion likelihood.
    - Referrals have higher chance of promotion compared to recruitment from other channels.
    - Promotional chances are not equal across departments and regions.
    - The ML model is accurate identifying eligible candidates but too conservative to find many of them due to lack of data from promoted employees.

- **Business Recommendations**
    - Enhance employee evaluation and training system to ensure truthful reflection of employee performance and better preparation for leadership role.
    - Assess and align recruitment quality across all channels, but also leverage referrals' strength when proper.
    - Investigate reasons behind departmental descrepencies and avoid biases.
    - Utilize the ML model to short-list candidates for promotion, take action to acquire more data from promoted employee to improve performance of the model.
