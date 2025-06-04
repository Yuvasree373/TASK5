# TASK5
Decision Trees and Random Forests

📌 Objective:

To explore and evaluate tree-based machine learning models — Decision Trees and Random Forests — for a classification problem using the Heart Disease Health Indicators dataset.

📂 Dataset:

Heart Disease Health Indicators (BRFSS 2015)
Source: Kaggle Dataset

Binary classification: HeartDiseaseorAttack (1 = Yes, 0 = No)

Features include: BMI, Smoking, Physical Activity, HighBP, Diabetes, Mental Health, etc.


✅ Key Tasks Completed:

1. Trained a Decision Tree Classifier:

Used scikit-learn to build the model.

Target variable: HeartDiseaseorAttack.

Visualized the tree structure using Graphviz.



2. Analyzed Overfitting:

Controlled tree complexity with max_depth, min_samples_split.

Observed accuracy trade-offs with pruning.



3. Trained a Random Forest Classifier:

Compared accuracy and generalization with the Decision Tree.

Found improved performance through ensembling.



4. Interpreted Feature Importances:

Used .feature_importances_ to identify key predictors.



5. Cross-Validation Evaluation:

Applied 5-fold cross-validation using cross_val_score.

Reported fold-wise and average accuracy.

🛠️ Tools & Libraries Used:

Python

Pandas

Scikit-learn

Graphviz

Matplotlib / Seaborn (optional for visualizations)

📈 Sample Results:

Decision Tree Accuracy: ~74%

Random Forest Accuracy: ~78–80%

Important Features: HighBP, BMI, Smoking, Age, Physical Activity

🔍 Insights:

Random Forests reduce overfitting and perform better on unseen data.

Feature importance helps in understanding key health indicators influencing heart disease.

