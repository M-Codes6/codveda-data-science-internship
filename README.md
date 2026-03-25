# 📊 Codveda Data Science Internship

This repository contains projects completed during my Data Science Internship at Codveda Technologies.  
These projects cover data analysis, visualization, and machine learning.

---

# 🚀 Projects

---

## 🔹 1. Web Scraping Project

- Scraped quotes and author information using Python  
- Implemented pagination to collect data from multiple pages  
- Used `requests` and `BeautifulSoup`  
- Stored structured data in CSV format  

📁 Output: `quotes_dataset.csv`

---

## 🔹 2. House Price Data Analysis (EDA)

- Performed Exploratory Data Analysis on housing dataset  
- Analyzed relationships between features and house prices  
- Visualized data using `matplotlib` and `seaborn`  

### 📊 Key Insights:
- Number of rooms positively impacts price  
- Lower income population negatively impacts price  
- Data shows strong correlations between multiple features  

---

## 🔹 3. Customer Churn Prediction (Machine Learning)

This project predicts whether a customer will churn based on usage patterns.

### 🔧 Steps Performed:
- Data Cleaning & Preprocessing  
- Feature Encoding (categorical → numeric)  
- Train-Test Split (80-20)  
- Feature Scaling  
- Model Training & Evaluation  

---

### 🤖 Models Used:

#### 🔸 Logistic Regression
- Accuracy: ~86%  
- Recall (Churn): Low  

#### 🔸 Random Forest
- Accuracy: ~95%  
- Recall (Churn): ~71%  

---

### 📈 Key Insight:
In churn prediction, **recall is more important than accuracy** because missing a churn customer leads to business loss.

---

### 🏆 Final Conclusion:
Random Forest performed significantly better than Logistic Regression by improving both accuracy and recall.

---

## 🔹 4.Customer Segmentation using K-Means (Unsupervised Learning)

🔹 Applied K-Means clustering to segment customers based on income and spending behavior  
🔹 Used Elbow Method to determine the optimal number of clusters  
🔹 Visualized clusters and identified distinct customer groups  

📊 **Key Insight:**  
Different customer segments exhibit different spending patterns, enabling businesses to design targeted marketing strategies.


---

# 🛠️ Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- BeautifulSoup  
- Requests  

---

# 🎓 Internship

**Data Science Internship**  
Codveda Technologies  

---

# 💡 Future Improvements

- Apply SMOTE for better imbalance handling  
- Try advanced models (XGBoost, Gradient Boosting)  
- Perform hyperparameter tuning  