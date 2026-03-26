## 📌 Overview
👨‍💻 Built as part of my learning journey to become a Data Scientist.

This repository showcases my end-to-end journey in Data Science, covering:
- Data Collection (Web Scraping)
- Data Analysis (EDA)
- Machine Learning (Classification & Regression)
- Unsupervised Learning (Clustering)



## 📊 Codveda Data Science Internship

This repository contains projects completed during my Data Science Internship at Codveda Technologies.  
These projects demonstrate end-to-end data science workflows including data collection, analysis, visualization, and machine learning.

---

# 🚀 Projects

1. Web Scraping Project (Data Collection)
2. House Price Data Analysis (EDA)
3. Customer Churn Prediction (Machine Learning)
4. Customer Segmentation using K-Means (Unsupervised Learning)
5. House Price Prediction (Regression)


---

## 🔹 1. Web Scraping Project
      📓 Notebook: notebooks/01_web_scraping.ipynb

- Scraped quotes and author information using Python  
- Implemented pagination to collect data from multiple pages  
- Used `requests` and `BeautifulSoup`  
- Stored structured data in CSV format  

📁 Output: `quotes_dataset.csv`

---

## 🔹 2. House Price Data Analysis (EDA)
      📓 Notebook: notebooks/02_house_price_analysis.ipynb

- Performed Exploratory Data Analysis on housing dataset  
- Analyzed relationships between features and house prices  
- Visualized data using `matplotlib` and `seaborn`  

### 📊 Key Insights:
- Number of rooms positively impacts price  
- Lower income population negatively impacts price  
- Data shows strong correlations between multiple features  

---

## 🔹 3. Customer Churn Prediction (Machine Learning)
      📓 Notebook: notebooks/03_churn_predictio.ipynb

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

## 🔹 4. Customer Segmentation using K-Means (Unsupervised Learning)
      📓 Notebook: notebooks/04_clustering_customer_segmentation.ipynb

🔹 Applied K-Means clustering to segment customers based on income and spending behavior  
🔹 Used Elbow Method to determine the optimal number of clusters  
🔹 Visualized clusters and identified distinct customer groups  

📊 **Key Insight:**  
Different customer segments exhibit different spending patterns, enabling businesses to design targeted marketing strategies.

---


### 🔹 5. House Price Prediction (Regression)
    📓 Notebook: notebooks/05_house_price_prediction.ipynb

🔹 Built a Linear Regression model to predict house prices  
🔹 Used housing dataset with multiple features  
🔹 Split data into training and testing sets  
🔹 Evaluated model using R2 Score and Mean Squared Error  

📊 **Key Insight:**  
The model can reasonably predict house prices, but performance can be improved using advanced algorithms.



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



⭐ If you find this useful, consider giving a star!