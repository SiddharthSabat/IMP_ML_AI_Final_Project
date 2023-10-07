# Heart Disease Prediction with Hyperparameter Optimization (Bayesian Optimization)

## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
This project employs machine learning to predict the presence of heart disease in patients. Using a dataset containing various health metrics and personal information, we implement a Random Forest Classifier model to determine the likelihood of heart disease. Hyperparameters are optimized using Bayesian optimization to enhance the model's accuracy and reliability. The output provides clear insights into the model's performance and can be a valuable tool for healthcare professionals to quickly assess and diagnose patients, leading to faster and more effective treatments.

## DATA
The dataset is obtained from the UCI Machine Learning Repository, specifically the [Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease). It consists of 303 instances and 14 attributes, including age, sex, chest pain type, resting blood pressure, cholesterol level, and others. The target variable indicates the presence and stage of heart disease, with values ranging from 0 (no presence) to 4 (Stage 4 heart disease).

## MODEL
We utilize the Random Forest Classifier for this task due to its robustness, ease of use, and ability to handle a mix of numerical and categorical variables. Random Forest is an ensemble learning method that operates by constructing multiple decision trees during training and outputting the class that is the mode of the classes or mean prediction of the individual trees.

## HYPERPARAMETER OPTIMIZATION
Bayesian Optimization is employed to optimize the hyperparameters of the Random Forest model. We optimize four hyperparameters: the number of estimators, maximum depth of the trees, minimum samples split, and minimum samples leaf. The optimization aims to find the set of hyperparameters that yields the highest model performance, measured using accuracy.

## RESULTS
The optimized model achieves an accuracy of approximately 91.8%. The confusion matrix provides insights into the true positive, true negative, false positive, and false negative predictions, offering a comprehensive view of the model's performance.

![Screenshot](confusion_matrix.png)


## REFLECTION ON ML/AI APPLICATION TO CAREER GOALS
Machine learning and artificial intelligence are transforming every industry, including healthcare. In this project, the application of a Random Forest Classifier optimized using Bayesian Optimization to predict heart disease exemplifies the potential of AI/ML in diagnostics and personalized medicine. For professionals aiming to transition or grow their careers in AI/ML, projects like these offer invaluable experience in tackling real-world problems, dealing with data imperfections, and optimizing models for performance, which are crucial skills in the professional realm. It underscores the importance of continual learning and adaptation to leverage AI/ML for innovative solutions.

## REAL-LIFE DATA CHALLENGE IN HEALTHCARE
The Bayesian optimization applied to the heart disease prediction model demonstrates its efficacy in a real-world healthcare scenario. By optimizing the model’s hyperparameters, we ensure the model is as accurate and reliable as possible. This practice is essential in healthcare, where model predictions can significantly impact patient diagnosis, treatment, and outcomes. It exemplifies the intersection of data science and healthcare and underscores the opportunities for professionals to contribute to enhanced patient care through AI/ML.

## CONTACT DETAILS
For more information or questions about this project, feel free to reach out on Linkedin [@SiddharthSabat](https://ae.linkedin.com/in/sidharthsabat88) or via email at siddharthsabat@gmail.com
