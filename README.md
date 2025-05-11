
# 📊 Social Network Ads - Feature Scaling and Analysis

This project demonstrates the preprocessing and analysis of a **Social Network Ads** dataset, focusing mainly on **feature scaling** techniques and their impact on model performance.

## 🧠 Objective

The goal is to predict whether a user purchases a product based on features like:

* Age
* Estimated Salary

The target variable is **Purchased** (0 or 1).

---

## 🔍 Key Concepts Covered

### ✅ Feature Scaling

Feature scaling is essential in this dataset due to large differences in feature magnitudes (e.g., Age vs Salary). We apply:

* **Standardization** using `StandardScaler`
* Comparisons with and without scaling using different models

### ✅ Data Preprocessing

* Handling missing values (if any)
* Encoding categorical variables (if gender or other categories are included)
* Splitting dataset into train and test sets

---

## ⚙️ Tech Stack

* Python 🐍
* NumPy / Pandas
* Matplotlib / Seaborn
* Scikit-learn

---

## 🚀 Workflow

1. **Importing the dataset**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Scaling**

   * Before scaling: compare performance
   * After scaling: observe improvements
4. **Model Training**

   * Logistic Regression / SVM / KNN
5. **Evaluation**

   * Confusion matrix
   * Accuracy score
   * Visualization of decision boundaries (2D plot)

---

## 📈 Results

Feature scaling significantly impacts algorithms like:

* **KNN**: Distance-based → scaling improves accuracy drastically
* **SVM**: Sensitive to feature magnitudes
* **Logistic Regression**: Less sensitive, but still benefits from normalization

---

## 📂 File Structure

```
├── social_network_ads_analysis/
│   ├── social_network_ads.csv
│   ├── feature_scaling_analysis.ipynb
│   └── README.md
```

---

## 📝 How to Run

```bash
git clone https://github.com/yourusername/social-network-ads-analysis.git
cd social-network-ads-analysis
jupyter notebook feature_scaling_analysis.ipynb
```

---

## 📬 Contact

For queries or contributions, feel free to connect on [LinkedIn](https://linkedin.com/in/satyam-mishra-9329a1329) or raise an issue.

