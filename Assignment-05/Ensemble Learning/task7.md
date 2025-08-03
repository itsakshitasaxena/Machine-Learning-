
# Ensemble Learning – Bagging, Boosting, Random Forest

**1. What is the difference between Bagging and Boosting?**
- Bagging (Bootstrap Aggregating) builds multiple models in parallel using random subsets of the data and then averages or votes their predictions to reduce variance (e.g., Random Forest).

- Boosting builds models sequentially, where each new model focuses on correcting the errors of the previous ones to reduce bias (e.g., AdaBoost, XGBoost).

**2. How does Random Forest reduce variance?**
    Random Forest reduces variance by combining predictions from multiple decision trees trained on different bootstrapped samples and random subsets of features. The aggregation (majority vote or average) helps smooth out individual tree overfitting, improving generalization.

**3. What is the weakness of boosting-based methods?**
    Boosting methods can be sensitive to noisy data and outliers, as each new learner tries to fix previous errors, possibly amplifying noise. They can also be computationally expensive and prone to overfitting if not properly regularized.