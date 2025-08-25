# Diabetes-Prediction
This project demonstrates how machine learning models can be applied to healthcare to predict the likelihood of diabetes in patients based on diagnostic health features. Using Python, TensorFlow/Scikit-learn, and common data science libraries, the workflow covers data preprocessing, model building, evaluation, and prediction.

The Accuracy of the Model is around 70%

Dowload the Dataset from Kaggle -> https://www.kaggle.com/datasets/mathchi/diabetes-data-set [diabetes.csv]

Co realational Heatmap for Diabetes ->
<img width="1440" height="707" alt="Screenshot 2025-08-25 at 2 04 31 PM" src="https://github.com/user-attachments/assets/a0311341-1cf6-4e6f-8f39-203b1c5c1821" />

Accuracy for K-Neighbour Classifier ->
<img width="1440" height="213" alt="Screenshot 2025-08-25 at 2 08 21 PM" src="https://github.com/user-attachments/assets/f10c30f9-1fb0-4c54-9190-af4a5120a831" />

Accuracy for Decision Tree Classifier ->
<img width="1440" height="292" alt="Screenshot 2025-08-25 at 2 06 00 PM" src="https://github.com/user-attachments/assets/56681384-b076-4f65-a4ce-496a8fa79c5c" />

Accuracy for Standard Scaler Classifier ->
<img width="1440" height="398" alt="Screenshot 2025-08-25 at 2 05 22 PM" src="https://github.com/user-attachments/assets/faecbeb9-91ef-454a-94cc-1c6a3025ee49" />


📊 Dataset

The project uses a standard diabetes dataset (e.g., PIMA Indians Diabetes Dataset from UCI repository).
Features include glucose level, BMI, age, insulin, blood pressure, pregnancies, and more.
Target variable: Diabetes outcome (0 = No, 1 = Yes).

⚙️ Methodology

Data Preprocessing – Handling missing values, normalization, and feature scaling.
Exploratory Data Analysis (EDA) – Understanding distributions and correlations.
Model Training – Using ML algorithms (Logistic Regression, Decision Tree, Random Forest, Neural Network).
Evaluation – Calculating accuracy, precision, recall, F1-score, and plotting confusion matrix.
Prediction – Model can predict if a new patient is diabetic based on input features.

📈 Results

Achieved good classification accuracy on the dataset (insert actual accuracy here, e.g., 85%).
Models show promising results in predicting diabetes risk from health indicators.
Neural Network/Random Forest generally outperform baseline models.
