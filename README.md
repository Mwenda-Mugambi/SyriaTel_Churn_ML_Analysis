
# SyriaTel Customer Churn Prediction

## Overview
In this project, we aimed to predict customer churn for SyriaTel, a telecommunications company. By leveraging data, our goal was to gain insights into why customers might be leaving and to develop strategies to retain them.

## Business and Data Understanding
**Stakeholder Audience:** Our primary stakeholders are the Marketing and Retention Department of SyriaTel. The insights and predictions from this project will help them make informed decisions about customer retention strategies, marketing campaigns, and service improvements.

**Dataset Choice:** We used the Churn in Telecom's dataset, which provides a comprehensive view of customer profiles, their usage patterns, and churn status. This dataset offers a mix of categorical and numerical features, providing a holistic view of customer behaviors and preferences.

## Modeling
Our modeling journey began with a baseline model using Logistic Regression. This helped set a performance benchmark. We then explored more complex models like Decision Trees and Random Forests to improve upon the baseline.

## Evaluation
Model performance was primarily evaluated using the ROC-AUC score, precision, and recall. The Random Forest model emerged as the most effective, achieving the highest ROC-AUC score among the models we tried.

### Key Findings

1. **Baseline Model (Logistic Regression)**:
    - ROC-AUC Score: 0.7165
    - Precision for predicting churn: 0.33
    - Recall for predicting churn: 0.67

2. **Decision Tree**:
    - ROC-AUC Score: 0.8199
    - Precision for predicting churn: 0.60
    - Recall for predicting churn: 0.72

3. **Random Forest**:
    - ROC-AUC Score: 0.8837
    - Precision for predicting churn: 0.85
    - Recall for predicting churn: 0.79


## Conclusion
Among the models we tested in predicting customer churn rates at SyriaTel Communications, the **Random Forest** emerged as the most effective in predicting customer churn.

[image here]

Features like **'customer service calls'**, and the **'total day minutes'**. were consistently highlighted as significant predictors of churn. This suggests that daily charges which had direct linear relationship with **daily minutes**, and the quality of customer service, are areas where customer dissatisfaction may arise, leading to churn.

[image here]

## Recommendations

* **SyriaTel should Focus on Customer Service:** A significant number of customer service calls is a strong predictor of churn. This suggests that customers who experience issues or dissatisfaction often turn to customer service. 

* **Review Pricing Structure:** It would be worthwhile to analyze the pricing structure, especially for day-time charges, and see if it aligns with competitors and the perceived value by the customers.

* **Continuous Monitoring:** Customer behaviors and preferences evolve. It's crucial to continuously monitor and update the model to reflect new data and insights.

* **Expand Model Exploration:** While the Random Forest model performed well, there's always room for improvement. Advanced models, further hyperparameter tuning, and additional feature engineering could enhance predictive performance.

* SyriaTel should consider running targeted surveys or focus groups with customers, especially those identified as 'at-risk' by the model. Direct feedback can provide more context and depth to the insights gathered from the data.

* **Implement Retention Strategies:** For customers predicted to churn.

By proactively addressing the areas of concern highlighted by our models and implementing the above recommendations, SyriaTel can significantly mitigate customer churn and enhance customer loyalty and satisfaction.