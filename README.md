# 📊 Amazon Product Data Analysis & Price Prediction

## 📌 Project Overview
This project analyzes Amazon product listings to uncover pricing strategies, discount distributions, and feature correlations. A **Linear Regression** model was trained using Python in Google Colab to predict discounted product prices based on historical features.

---

## 🛠️ Tools & Technologies
* **Language:** Python
* **Environment:** Google Colab
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (Linear Regression)

---

## 🔄 Project Workflow
1. **Data Cleaning & Preprocessing:** Handled missing values, formatted currency strings, and stripped special characters.
2. **Exploratory Data Analysis (EDA):** Analyzed price distributions, rating patterns, and outliers using boxplots.
3. **Feature Selection & Correlation:** Measured relationships between numerical features using a heatmap.
4. **Model Training:** Built and evaluated a Linear Regression model for price prediction.
5. **Business Insights:** Derived key conclusions regarding discount strategies.

---
## 📈 Key Visualizations & Insights

### 1. Correlation Matrix
* **Insight:** Actual Price has the strongest positive correlation with Discounted Price.
![Correlation Matrix](images/sales1.png)

### 2. Discounted Price Distribution
* **Insight:** Most products are concentrated in the lower price range with a long right tail.
![Discounted Price Distribution](images/sales2.png)

### 3. Actual Price Distribution
* **Insight:** Original prices show a similar right-skewed distribution as discounted prices.
![Actual Price Distribution](images/sales3.png)

### 4. Ratings Distribution
* **Insight:** Majority of the products have high ratings clustered between 3.8 and 4.5.
![Ratings Distribution](images/sales4.png)

### 5. Outlier Analysis (Boxplot)
* **Insight:** Significant outliers are present in rating counts and price fields.
![Boxplot for Outliers](images/sales5.png)

### 6. Actual Price vs. Discounted Price
* **Insight:** Demonstrates a strong linear relationship between base price and discounted price.
![Actual vs Discounted Price](images/Sales6.png)

### 7. Rating vs. Discounted Price
* **Insight:** Product ratings do not directly dictate price points or discounts.
![Rating vs Discounted Price](images/sales7.png)
---

## 🎯 Model Performance
* **Algorithm:** Linear Regression
* **Evaluation Metrics:** *(Yahan apna R2 Score aur MAE/RMSE add karein, e.g., R² Score: 0.92)*

---

## 💡 Key Takeaways
* High-priced items carry larger absolute discounts, but discount percentage varies widely.
* Product popularity (ratings and review counts) does not significantly impact pricing models.

---

## 👤 Author
* **Saloni Gupta**
* [LinkedIn Profile](Aapka_LinkedIn_Link) | [GitHub Profile](Aapka_GitHub_Link)
