# Heart-Disease-Prediction Using Logistic Regression

## Project Overview
The goal of this project is to utilize logistic regression to accurately predict whether an individual has heart disease based on various health metrics.

## Dataset
1. Source: The dataset is a collection of health metrics from individuals, with a target variable indicating the presence (1) or absence (0) of heart disease.
2. Features: Includes age, sex, chest pain type (cp), resting blood pressure (trestbps), serum cholesterol (chol), fasting blood sugar (fbs), resting electrocardiographic results (restecg), maximum heart rate achieved (thalach), exercise-induced angina (exang), oldpeak, slope, number of major vessels colored by fluoroscopy (ca), and thalassemia (thal).
3. Target: Heart disease presence indicated as 0 (no presence) and 1 (presence).

## Data Preprocessing
1. Null Value Handling: Checked and confirmed that there are no missing values in the dataset.
2. Feature-Target Split: Separated the dataset into features (x) and the target variable (y).
3. Train-Test Split: Split the data into training and testing sets to evaluate the model's performance accurately.

## Model Training
1. Algorithm: Logistic Regression from the sklearn.linear_model package.
2. Training: The model is trained on the training set consisting of features and the corresponding target variable.

## Model Evaluation
1. Training Data Accuracy: Evaluated the model on the training set to ensure it learns appropriately.
2. Testing Data Accuracy: Evaluated the model on the unseen test set to check for overfitting and obtain an unbiased performance metric.
3. Accuracy Scores: Achieved an accuracy of ~85.12% on the training data and ~81.97% on the test data.

## Predictive System
1. Demonstrated the model's prediction capability with a sample input.
2. The predictive system preprocesses the input, applies the trained logistic regression model, and outputs whether the individual is predicted to have heart disease.

## How to Use
1. Clone the repository.
2. Ensure you have numpy, pandas, and sklearn installed in your Python environment.
3. Load your dataset or use the provided heart_disease_data.csv file.
4. Run the logistic regression model training and evaluation steps.
5. Use the predictive system with new data to make predictions.

## Contributions
Contributions to this project are welcome! Feel free to fork the repository, make improvements, and submit a pull request. If you encounter any issues or have suggestions, please open an issue on the GitHub repository page.
