#  Week 1 Tasks

---

## ✅ Task 1: Titanic Dataset EDA

### ⚙️ Steps Performed  
1. Performed **Data cleaning**:  
   - Filled missing values (Age → Median, Fare → Mean)  
   - Removed duplicates  
2. Created visualizations:  
   - Survival count by gender (bar chart)  
   - Age distribution (histogram)  
   - Correlation heatmap  
3. **Key Insights:**  
   - Females had a higher survival rate than males  
   - Younger passengers had better survival chances  
   - Higher class passengers (Pclass 1) had better chances of survival  
   - Fare correlated positively with survival  

---

## ✅ Task 2: Sentiment Analysis (IMDB Reviews)

### ⚙️ Steps Performed  
1. Preprocessed reviews:  
   - Lowercased text  
   - Removed stopwords & special characters  
2. Converted text into numerical format using **CountVectorizer (Bag of Words)**  
3. Trained a **Logistic Regression model**  
4. **Evaluation:**  
   - Accuracy: `0.8735%`  
5. **Example Predictions:**  
   - "This movie was fantastic! I loved the story and acting." → Positive  
   - "Worst film ever. Completely boring and a waste of time." → Negative  

### 📂 Dataset  
**IMDB Movie Reviews**  
🔗 [View Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

---

## ✅ Task 3: Predicting House Prices (Boston Housing Dataset)

### ⚙️ Steps Performed  
1. Normalized numerical features using **StandardScaler**  
2. Trained a **Linear Regression model**  
3. **Evaluation:**  
   - Root Mean Squared Error (RMSE): `4.928602182665336`  
4. **Example Prediction:**  
   - Predicted price for sample house: `28.996723619824877`  
   - Actual price: `23.6`  

---

### 📌 All tasks include:
- Clean, well-commented Jupyter Notebooks  
- Visualizations where applicable  
- Short summary of results  

---

#  Week 2 Tasks

---

## 🧠 Task 1: Term Deposit Subscription Prediction (Bank Marketing)

### 🎯 Objective  
Predict whether a bank customer will subscribe to a term deposit after a marketing campaign.

### 📂 Dataset  
**Bank Marketing Dataset – UCI Machine Learning Repository**  
🔗 [View Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

### 🧰 Tools & Libraries  
`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `shap`

### ⚙️ Steps Performed  
- Loaded and explored the dataset  
- Encoded categorical features using **LabelEncoder**  
- Trained **Logistic Regression** and **Random Forest** models  
- Evaluated using **Confusion Matrix**, **F1-Score**, and **ROC Curve**  
- Applied **SHAP (Explainable AI)** to interpret 5 model predictions  

### 📊 Results & Insights  
- **Random Forest** achieved the best **F1-score** and **ROC-AUC**.  

---

## 👥 Task 2: Customer Segmentation Using Unsupervised Learning

### 🎯 Objective  
Cluster mall customers based on spending habits and suggest marketing strategies for each segment.

### 📂 Dataset  
**Mall Customers Dataset**

### 🧰 Tools & Libraries  
`pandas`, `matplotlib`, `seaborn`, `sklearn (KMeans, PCA)`

### ⚙️ Steps Performed  
- Performed **EDA** to understand spending behavior and income distribution  
- Applied **K-Means Clustering** to create customer segments  
- Used **PCA** for 2D visualization of clusters  
- Suggested targeted marketing strategies based on cluster profiles  

### 📊 Results & Insights  
- Identified **3 main customer segments**:  
  - 🏷️ **High spenders** – target with premium offers  
  - 🛒 **Average customers** – loyalty rewards  
  - 💸 **Low spenders** – discount campaigns  
- Helped understand spending diversity and potential revenue sources.  

---

## 📈 Task 3: Interactive Business Dashboard (Streamlit)

### 🎯 Objective  
Build an interactive dashboard for analyzing sales, profit, and customer performance.

### 📂 Dataset  
**Global Superstore Dataset**

### 🧰 Tools & Libraries  
`streamlit`, `pandas`, `plotly.express`

### ⚙️ Steps Performed  
- Cleaned and loaded the dataset  
- Built a **Streamlit dashboard** with sidebar filters for Region, Category, and Sub-Category  
- Displayed key performance indicators (KPIs):  
  - 💰 **Total Sales**  
  - 📈 **Total Profit**  
  - 🏆 **Top 5 Customers by Sales**  
- Created **interactive bar and pie charts** using Plotly  

### 📊 Results & Insights  
- Dashboard allows **dynamic filtering** and **real-time business analysis**  
- Helps management easily track **sales trends** and **top-performing regions**  

---

### 🧠 Author  
**Muhammad Unais**  
Artificial Intelligence | Dawood University  
