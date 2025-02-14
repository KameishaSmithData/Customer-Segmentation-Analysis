# E-Commerce Customer Segmentation & Behavior Analysis  

## 📌 Overview  
This project analyzes customer behavior to segment e-commerce customers and predict their spending patterns. By using clustering techniques and regression models, we uncover key insights into how customer engagement on mobile apps and websites affects yearly spending.  

## 📊 Dataset  
- **Dataset Name:** `Ecommerce Customers.csv`  
- **Source:** Contains customer demographics, online behavior, and spending habits.  
- **Key Features:**  
  - `Time on App`: Minutes spent on the mobile app  
  - `Time on Website`: Minutes spent on the website  
  - `Length of Membership`: How long a customer has been a member  
  - `Yearly Amount Spent`: The target variable for prediction  

## 🔍 Key Findings  
✔️ **Customers with longer membership tend to spend more.**  
✔️ **Website users spend about 3x more time than mobile users.**  
✔️ **Time spent on the mobile app has a slight correlation with yearly spending.**  
✔️ **Recommendation:** Improve the app experience by understanding which website features drive engagement and ensuring they are readily available on mobile.  

## 🛠️ Skills & Tools Used  
- **Python:** Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn  
- **EDA (Exploratory Data Analysis):** Heatmaps, scatterplots, statistical summaries  
- **Customer Segmentation:** K-Means Clustering  
- **Predictive Modeling:** Linear Regression for spending prediction  

## 📈 Project Steps  
1️⃣ **Load & Explore Data**  
   - Check for missing values & duplicates  
   - Generate dataset summary (`.describe()` & `.info()`)  
   - Visualize distributions (histograms, boxplots)  

2️⃣ **Exploratory Data Analysis (EDA)**  
   - Correlation Heatmap  
   - Scatterplots (e.g., Time on App vs. Yearly Spending)  

3️⃣ **Customer Segmentation (Clustering)**  
   - K-Means Clustering on:  
     - `Time on App`  
     - `Time on Website`  
     - `Length of Membership`  
     - `Yearly Amount Spent`  
   - Determine optimal clusters using the **Elbow Method**  

4️⃣ **Predict Customer Spending (Regression)**  
   - Train a **Linear Regression Model** to predict **Yearly Amount Spent**  
   - Compare website vs. mobile app engagement trends  
   - Evaluate model performance (**R² Score, Mean Absolute Error**)  

5️⃣ **Insights & Recommendations**  
   - Identify features that impact **spending the most**  
   - Determine if **mobile users** spend more than **website users**  
   - Suggest strategies to **increase customer retention**  

## 📁 Project Files  
📂 **data/**  
  - `ecommerce_customers.csv` (Raw dataset)  

📂 **notebooks/**  
  - `e-commerce-customer-segmentation.ipynb` (Jupyter Notebook)  

📂 **images/**  
  - `feature_correlation_heatmap.png`  
  - `time_on_website_vs_time_on_app.png`  
  - `time_on_app_vs_spending.png`  
  - `correlation_matrix_dotted_heatmap.png`  

## 🚀 Next Steps  
✅ Apply advanced **Machine Learning Models** for better segmentation  
✅ Create an **interactive dashboard** using **Power BI or Tableau**  
✅ Analyze customer behavior trends over time  

🔗 **Check out the full analysis here:** 

https://github.com/KameishaSmithData/Customer-Segmentation-Analysis
