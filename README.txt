🫀 Heart Disease Prediction using Decision Tree & Random Forest

This project uses Machine Learning classification models to predict the presence of heart disease based on medical attributes. It demonstrates model training, evaluation, visualization, and performance comparison between Decision Tree and Random Forest classifiers.

📁 Project Structure

heart.csv – Dataset containing patient medical data and heart disease labels

heart_disease_ml.py – Main script for data analysis and model training

🚀 Features

Data loading and preprocessing

Missing value check

Train-test data splitting

Decision Tree Classifier: training, evaluation, visualization, and overfitting analysis

Random Forest Classifier: training, evaluation, and feature importance ranking

Cross-validation for robust performance estimation

📊 Results

Accuracy scores and classification reports for both models

Overfitting analysis with accuracy vs. tree depth graph

Decision tree visualization

Feature importance plot for Random Forest

🛠️ Requirements

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

▶️ How to Run

Place heart.csv in the project directory.

Run the script:

python heart_disease_ml.py

📈 Sample Output

Decision Tree Accuracy: ~80%

Random Forest Accuracy: ~85–90%

Cross-Validation Accuracy: ~86–90%

📌 Notes

You can tune hyperparameters like max_depth, n_estimators, and test_size to improve performance.

Visualizations help analyze overfitting and understand key medical features influencing predictions.