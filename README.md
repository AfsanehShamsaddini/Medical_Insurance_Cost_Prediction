# 🏥 Medical Insurance Cost Prediction

This project predicts individual medical insurance costs based on demographic and health-related features using various machine learning models.

---

## 📌 Objective
To analyze the factors influencing medical insurance costs and build predictive models to estimate charges for individuals.

---

## 📊 Dataset
- **Source**: `insurance.csv`
- **Features**:
  - `age`: Age of the primary beneficiary
  - `sex`: Gender (`male`, `female`)
  - `bmi`: Body Mass Index
  - `children`: Number of dependents
  - `smoker`: Smoking status (`yes`, `no`)
  - `region`: Residential region in the US (`northeast`, `northwest`, `southeast`, `southwest`)
  - `charges`: Target variable – individual medical costs billed by health insurance

---

## 🔍 Exploratory Data Analysis (EDA)
- Distribution plots for age, BMI, charges
- Count plots for categorical variables (sex, smoker, region, children)
- Correlation heatmap to understand numerical relationships
- Pie charts for categorical data distribution

---

## 🛠️ Preprocessing
- Encoding categorical variables (`sex`, `smoker`, `region`)
- Removing duplicate rows
- No missing values detected

---

## 🤖 Models Trained
- **Linear Regression**
- **XGBoost Regressor** (with GridSearchCV for hyperparameter tuning)
- **Decision Tree Regressor**
- **Random Forest Regressor**

---

## 📈 Model Evaluation Metrics
- **R² Score**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)** (for some models)

---

## 🧪 Key Findings
- Smoking has a strong positive correlation with charges
- Age and BMI also significantly influence insurance costs
- XGBoost and Random Forest performed better than Linear Regression in predictive accuracy

---

## 🚀 How to Run
# Clone the repository
git clone https://github.com/AfsanehShamsaddini/Medical_Insurance_Cost_Prediction.git

# Go to the repo directory
cd Medical_Insurance_Cost_Prediction

# Run the notebook
jupyter notebook Medical_Insurance_Cost_Prediction.ipynb
