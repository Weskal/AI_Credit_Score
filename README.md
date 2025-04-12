# 🧠 Credit Score Classification Model

This project aims to predict the **credit score classification** of clients based on their financial behavior and profile. It uses machine learning algorithms to build a classification model that learns from historical data and provides predictions for new customers.

## 📊 Dataset
The dataset includes features such as:
- Profession
- Credit Mix
- Payment Behavior
- Credit Score (target variable)

Categorical columns were encoded using `LabelEncoder`.

## ⚙️ Tools & Libraries
- Python
- Pandas
- Scikit-learn
  - `RandomForestClassifier`
  - `KNeighborsClassifier`
  - `train_test_split`, `accuracy_score`

## 🛠️ How it works
1. Load and preprocess data (`clientes.csv`)
2. Encode categorical features
3. Split data into training and test sets
4. Train two machine learning models:
   - Random Forest
   - K-Nearest Neighbors (KNN)
5. Evaluate accuracy of each model
6. Make predictions for a new dataset (`novos_clientes.csv`)

## ✅ Results
- **Random Forest Accuracy:** ~83%
- **KNN Accuracy:** ~74%

The Random Forest model was chosen for final predictions based on its superior performance.

## 📦 How to run
1. Clone this repository
2. Install dependencies: `pip install pandas scikit-learn`
3. Run the notebook or script in a Python environment (e.g., Jupyter)

## 📁 Files
- `clientes.csv`: training data
- `novos_clientes.csv`: new customers for prediction
- `credit_score_model.ipynb` or `.py`: main code

