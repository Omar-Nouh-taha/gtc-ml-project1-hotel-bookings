# Hotel Booking Demand Prediction

This project analyzes the **Hotel Bookings dataset** and builds machine learning models to predict **booking cancellations**. The workflow covers **data cleaning, exploratory data analysis (EDA), feature engineering, and model evaluation** using multiple classification algorithms.

---

## 📂 Dataset

The dataset used is **hotel\_bookings.csv**, which contains information about hotel reservations, including:

* Booking status (canceled or not)
* Guest demographics
* Booking dates
* Distribution channels
* Market segments
* Special requests

---


**Main libraries used:**

* `numpy`, `pandas` – data manipulation
* `matplotlib`, `seaborn`, `missingno` – visualization & missing values analysis
* `scikit-learn` – preprocessing, classification models, evaluation metrics
* `xgboost` – gradient boosting model

---

## 🧾 Project Workflow

1. **Data Loading & Cleaning**

   * Read dataset
   * Handle missing values
   * Remove/clip outliers

2. **Exploratory Data Analysis (EDA)**

   * Dataset summary
   * Distribution of features
   * Correlation with target (`is_canceled`)
   * Visualization of missing values

3. **Feature Engineering**

   * Encoding categorical variables (Label Encoding, One-Hot Encoding)
   * Derived features such as `Total_Guests`

4. **Modeling**

   * Random Forest Classifier
   * Gradient Boosting Classifier
   * XGBoost Classifier

5. **Evaluation**

   * Train/test split
   * Cross-validation (K-Fold)
   * Classification reports (Precision, Recall, F1-score)

---

## 📊 Results

The models were compared using accuracy and classification metrics.

* Random Forest: Competitive baseline
* Gradient Boosting: Improved performance
* XGBoost: Best-performing model (highest accuracy & F1-score)

---



## 📌 Author

**Omar Nouh Taha**

* Data Scientist || Machine Learning Engineer
* [LinkedIn](https://www.linkedin.com/in/omar-nouh-taha)

---

Do you want me to also **add the exact accuracy/F1 scores from your notebook runs** into the “📊 Results” section so it looks more concrete on GitHub?
