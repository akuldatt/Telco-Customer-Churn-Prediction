# Telco Customer Churn Prediction & Analysis
A complete machine learning and analytics project using the Telco Customer Churn dataset.
This project covers data cleaning, exploratory analysis, churn pattern visualizations, multiple ML model comparisons, feature importance insights, and saving the best model for future use.

📁 Project Structure
data/ — Raw input CSV file(s)

notebooks/ — Jupyter Notebook(s) for EDA and modeling

outputs/ — Saved plots and figures

models/ — Trained model file (best_model.pkl)

README.md — Project overview and instructions

requirements.txt — Python dependencies

.gitignore — Files and folders to exclude from version control

🛠 Tools & Technologies
Python (Pandas, NumPy, Seaborn, Matplotlib)

Scikit-learn, XGBoost

Jupyter Notebook

Git and GitHub

🔍 Key Features
Data cleaning and preprocessing

Exploratory Data Analysis with multiple churn visualizations

Multiple machine learning models: Logistic Regression, Decision Tree, Random Forest, XGBoost, Voting Classifier

Confusion Matrix and ROC Curve visualizations

Feature Importance analysis using Random Forest

Saved best model for deployment (best_model.pkl)

Model performance comparison chart

📦 How to Run
Clone the repository to your local machine

Install all required Python libraries listed in requirements.txt

Open the Jupyter Notebook in the notebooks folder

Run the notebook to reproduce analysis, visualizations, and model training

Explore all output plots and results in the outputs folder

Use the saved model for predictions on new customer data

📈 Insights & Recommendations
Customers with month-to-month contracts and high monthly charges have higher churn rates.

Shorter tenure indicates a higher probability of churn — retaining new customers is key.

The type of internet service and additional services influence churn likelihood.

Among all models tested, Random Forest performed the best with an accuracy of about 82%.

## 📊 Visualization Previews

### Churn by Contract Type  
![Churn by Contract Type](images/Churn by Contract Type.png)

### Tenure vs Churn  
![Tenure vs Churn](images/tenure_vs_churn.png)

### Churn by Internet Service  
![Churn by Internet Service](images/churn_by_internet.png)

### Monthly Charges vs Churn  
![Monthly Charges vs Churn](images/monthly_charges_vs_churn.png)

### Confusion Matrix Heatmap  
![Confusion Matrix Heatmap](images/confusion_matrix_heatmap.png)

### ROC Curve (Random Forest)  
![ROC Curve](images/roc_curve_random_forest.png)

### Feature Importance (Random Forest)  
![Feature Importance](images/feature_importance_random_forest.png)

### Model Accuracy Comparison  
![Model Accuracy Comparison](outputs/model_accuracy_comparison.png)



