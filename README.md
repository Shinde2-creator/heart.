# Heart Disease Prediction Using Machine Learning: A Comparative Study of SVM, Random Forest, and Gradient Boosting
Implemented three models 
Example Findings Summary
In the study I designed and implemented three machine-learning models: a Support Vector Machine (SVM), a Random Forest (RF), and a Gradient Boosting Machine (GBM) to predict the presence of heart disease using a small subset of clinical health features.

After hyperparameter tuning was conducted SVM model achieved the highest overall accuracy of 90%, SVM also showed perfect precision when predicting cases of heart disease, Random Forest slightly outperformed SVM in area under the curve (AUC-ROC) at (0.9447). GBM performed well but across the board slightly lower.

Takeaways:
SVM has a solid baseline within the context of our research, demonstrated higher precision, and offered a good balance between sensitivity and specificity.
Random Forest has great explainability and scalability, performances and showed the best AUC.
Although the GBM model performed slightly behind the RF and SVM models it is still a strong option for boosting weak learners.
In summary, hyper-parameter tuning contributed to elevated performance across all models. This method will provide opportunity for healthcare practitioners to quickly identify at-risk patients. 
