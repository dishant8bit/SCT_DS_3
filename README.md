# 🌳 Bank Marketing Decision Tree Classifier

## 📌 Project Overview
This project builds a Decision Tree Classifier to predict whether a customer will subscribe to a product or service based on demographic and behavioral data. The model is trained using the Bank Marketing dataset and demonstrates a complete machine learning workflow including data preprocessing, feature encoding, model training, evaluation, and interpretation.

## 🗂 Dataset Description
The dataset contains customer information collected from marketing campaigns, including:

- Age  
- Job  
- Marital status  
- Education  
- Default  
- Balance  
- Housing loan  
- Personal loan  
- Contact type  
- Day and month of contact  
- Call duration  
- Campaign details  
- Previous campaign outcome  

**Target Variable**
- `y` → Customer subscription (`yes` / `no`)

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  

## ⚙️ Project Workflow
1. Load and inspect the dataset  
2. Fix delimiter and column formatting issues  
3. Handle categorical variables using encoding  
4. Split data into training and testing sets  
5. Train a Decision Tree Classifier  
6. Evaluate the model using accuracy, confusion matrix, and classification report  
7. Visualize the decision tree and feature importance  

## 📊 Model Used
- Decision Tree Classifier  
- Criterion: Gini Index  
- Simple, interpretable, and effective for classification tasks  

## 📈 Results
- Successfully trained a Decision Tree model  
- Achieved reliable classification performance  
- Identified key influencing features such as:
  - Call duration  
  - Previous campaign outcome  
  - Balance  
  - Campaign count  

## 📁 Project Structure
📦 bank-marketing-decision-tree
┣ 📜 bank.csv
┣ 📓 decision_tree.ipynb
┣ 📜 README.md
┗ 📜 requirements.txt

## 🚀 How to Run the Project
1. Clone the repository
git clone https:https://github.com/dishant8bit/SCT_DS_3.git

2. Install dependencies
pip install -r requirements.txt

3. Launch Jupyter Notebook
jupyter notebook

4. Open and run `decision_tree.ipynb`

## 📌 Future Improvements
- Hyperparameter tuning with GridSearchCV  
- Comparison with Random Forest and XGBoost  
- ROC–AUC curve analysis  
- Deployment using Streamlit  

## 👤 Author
Dishant Kudtarkar
