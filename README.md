This project aims to develop a machine learning model that accurately predicts Parkinson’s Disease using biomedical voice measurements. Parkinson’s Disease is a progressive neurological disorder that affects movement and speech. Early diagnosis can significantly improve patient outcomes, and this model serves as a decision-support tool to assist medical professionals in detecting the disease at an early stage.

✅ Key Features
Dataset: Uses a well-structured biomedical voice measurement dataset from the UCI Machine Learning Repository.

Preprocessing: Data cleaning, normalization, and feature selection techniques implemented to improve model performance.

Models Implemented:

Logistic Regression

Support Vector Machine (SVM)

Random Forest

K-Nearest Neighbors (KNN)

XGBoost

Evaluation Metrics:

Accuracy

Precision

Recall

F1-Score

ROC-AUC Curve

Visualization: Confusion matrix, correlation heatmap, and performance comparison charts included for analysis.

📁 Project Structure
css
Copy
Edit
├── dataset/
│   └── parkinsons.data
├── notebooks/
│   └── Parkinsons_Prediction.ipynb
├── src/
│   └── model.py
├── requirements.txt
└── README.md
⚙️ Technologies Used
Python

NumPy, Pandas

Scikit-learn

Matplotlib, Seaborn

XGBoost

📊 Dataset Information
Source: UCI ML Repository – Parkinson’s Disease Data Set

Features: 22 voice measurements per instance

Target: Status (1 = Parkinson’s Disease, 0 = Healthy)

📈 Results
The best-performing model achieves a high accuracy score, demonstrating its potential for aiding early diagnosis. Further improvements could be achieved by integrating more diverse datasets and deploying the model via a web application or mobile interface.

🚀 Future Scope
Model deployment with Flask/Django

Integration with real-time voice input

Improvement using deep learning techniques

Cross-validation with larger, real-world datasets

