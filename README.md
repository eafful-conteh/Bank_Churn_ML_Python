I built an end-to-end machine learning pipeline to predict customer churn for a bank.

I started with data preprocessing by converting the target variable into binary format and applying one-hot encoding to categorical features like gender, income category, and card type. I then split the data into training and test sets and built a modular pipeline using Pipeline to ensure proper preprocessing and avoid data leakage. For models sensitive to feature scale, like Logistic Regression, SVM, and KNN, I applied standardization. I trained multiple models including Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, AdaBoost, SVM, KNN, Naive Bayes. I used GridSearchCV with 5-fold cross-validation to tune hyperparameters.

For evaluation, I used accuracy, F1-score, and ROC-AUC, but focused primarily on F1-score to balance precision and recall.
The best-performing models were ensemble methods like Random Forest and Gradient Boosting, which captured nonlinear relationships effectively.

The model helps identify high-risk customers early. The key drivers of churn were low engagement, fewer transactions, and higher inactivity, which can inform targeted retention strategies.
