# Lung Cnacer Classification-Machine Learning Approaches Comparison

Lung cancer is one of the leading causes of cancer-related deaths worldwide, accounting for
millions of deaths every year. Early detection through non-invasive means can significantly
improve patient prognosis, but the complexity and variability of symptoms often delay diagnosis.
This research aims to identify the potential of machine learning (ML) models to predict the
likelihood of lung cancer using clinical data, including lifestyle habits, symptoms, and patient
demographics. Five algorithms were assessed including logistic regression (LR), random forest
(RF), K-nearest neighbors (KNN), support vector machines (SVM), and artificial neural
networks (ANNs). The dataset consisted of 309 instances with 16 features, including
demographics, smoking history, chest pain, chronic disease and other potential risk indicators.
To address class imbalance, Synthetic Minority Over-sampling Technique (SMOTE) was
applied, and data scaling was utilized for normalization. After hyperparameter optimization
using grid search and randomized search cross-validation, the models' performance was
evaluated using metrics like accuracy, precision, recall, and F1-score. The results show that the
ANN model achieved the highest test accuracy of 96.39%, outperforming the other approaches.
The best-performing model was implemented in a user-friendly graphical interface for practical
clinical application. This study provides valuable insights into the comparative strengths of
different machine learning techniques for lung cancer prediction and identifies the critical risk
factors that drive the models' predictive capabilities.


<img width="959" alt="GUI_Output_1 (LUNG CANCER DETECTED)" src="https://github.com/user-attachments/assets/03c9457c-1b3f-4dcf-b315-8b9beea3656f" />




<img width="959" alt="GUI_Output_2 ( NO LUNG CANCER DETECTED)" src="https://github.com/user-attachments/assets/de842c35-d70e-4311-a666-fccef03b20b4" />

