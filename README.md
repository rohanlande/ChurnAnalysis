# 📉 Customer Churn Analysis & Prediction Dashboard

This end-to-end project demonstrates how to perform Customer Churn Analysis using **SQL Server**, **Power BI**, and **Machine Learning (Random Forest in Python)**. The goal is to understand customer churn patterns and predict future churners.

---

## 🗂️ Project Structure

1. **ETL Process (SQL Server)**
   - Imported raw customer data (`Customer_Data.csv`) into a staging table.
   - Cleaned data and loaded it into a production table `prod_Churn`.
   - Created views (`vw_ChurnData`, `vw_JoinData`) for use in Power BI.

2. **Data Analysis (Power BI)**
   - Demographic, geographic, account, and service-based analysis.
   - Custom calculated columns: Age Group, Tenure Group, Monthly Charge Range.
   - Key metrics:
     - Total Customers
     - Total Churn & Churn Rate
     - New Joiners

3. **Dashboard Pages**
   - **Summary Page:** Churn trends by demographics, services, contracts, etc.
   - **Churn Reason Page:** Breakdown of churn categories and reasons.
   - **Prediction Page:** Shows future churners based on ML model.

4. **Churn Prediction Model (Python - Random Forest)**
   - Built using `pandas`, `sklearn`, `joblib`.
   - Trained on `vw_ChurnData`, predicted on `vw_JoinData`.
   - Predictions integrated back into Power BI for visualization.

---

## 📦 Tools & Technologies

- **SQL Server Management Studio (SSMS)** – ETL and data modeling
- **Power BI** – Data transformation and dashboards
- **Python (Jupyter Notebook)** – ML model for churn prediction
- **Random Forest Classifier** – Used for classification of churners

---

## 📌 Key Insights

- Identified high churn demographics and locations
- Analyzed service usage behavior of churners
- Predicted future churners to help plan targeted marketing


---

## 📬 Contact

**Rohan Lande**  
📧 rohanlande0310@gmail.com  
📍 Pune, India  
🔗 [LinkedIn](https://www.linkedin.com/in/rohanlande/)  

---

⭐ Star this repo if you found it useful!
