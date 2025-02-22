# LoanTap: Logistic Regression  

## 📌 Project Overview  
LoanTap is an online lending platform that provides customized personal loans. This project focuses on developing a **Logistic Regression model** to assess the creditworthiness of individuals and determine loan approval decisions.  

## 📊 Problem Statement  
Given a set of borrower attributes, predict whether a **personal loan** should be **approved or rejected** and provide business recommendations regarding repayment terms.  

## 📂 Dataset: `LoanTapData.csv`  
The dataset contains borrower details such as **loan amount, interest rate, employment length, home ownership, annual income, credit history, and loan status**.  

## 🛠 Key Concepts Used  
- **Exploratory Data Analysis (EDA)**  
- **Feature Engineering**  
- **Logistic Regression**  
- **Precision-Recall Tradeoff**  
- **Model Performance Evaluation**  

## 🏗 Project Workflow  

### 1️⃣ **Exploratory Data Analysis (EDA)**  
- Checked dataset structure, missing values, and distributions.  
- Analyzed **target variable dependency** using **count plots, box plots, and heatmaps**.  
- Identified **high-correlation features** and multicollinearity.  

### 2️⃣ **Feature Engineering & Data Preprocessing**  
- Created **binary flags** for public records, mortgage accounts, and bankruptcies.  
- Treated **missing values** and **outliers**.  
- Scaled numerical features using **MinMaxScaler / StandardScaler**.  

### 3️⃣ **Model Building: Logistic Regression**  
- Trained a **Logistic Regression model** using `sklearn` and `statsmodels`.  
- Evaluated performance using **ROC AUC, Precision-Recall Curve, and Classification Report**.  

### 4️⃣ **Model Performance & Tradeoffs**  
- Addressed **class imbalance** using **SMOTE** to enhance recall.  
- Balanced business risks by analyzing **false positives vs false negatives** tradeoff.  

### 5️⃣ **Insights & Business Recommendations**  
- High **loan default risk** observed in lower credit grades (F, G).  
- **Income verification and credit history** significantly impact loan approvals.  
- Business should **adjust approval thresholds** to **balance loan disbursement vs risk exposure**.  

## 🔍 Key Findings  

| Feature | Impact on Loan Status |
|---------|----------------------|
| **Annual Income** | Higher income reduces loan default risk |
| **Interest Rate** | Higher interest rates correlate with higher default probability |
| **Employment Length** | Longer employment tenure improves creditworthiness |
| **Home Ownership** | Mortgage owners have better repayment rates |

## 📌 Actionable Recommendations  
✔ Improve **feature engineering** to enhance model performance.  
✔ Regularly **update and retrain the model** with fresh data.  
✔ Implement a **risk-based pricing model** to adjust loan terms dynamically.  
✔ Conduct **geographic analysis** as loan default rates vary by location.  

## 🚀 Next Steps  
🔹 Experiment with **ensemble models (Random Forest, XGBoost) for better predictive accuracy**.  
🔹 Implement **threshold tuning** for optimized loan approval rates.  
🔹 Deploy the model in a real-world scenario for **real-time loan evaluation**.  

---

### 🏷️ **Tech Stack**  
✅ Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
✅ Logistic Regression  
✅ SMOTE for class imbalance handling  

---


