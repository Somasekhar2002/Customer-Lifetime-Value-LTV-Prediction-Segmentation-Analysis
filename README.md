# Customer-Lifetime-Value-LTV-Prediction-Segmentation-Analysis
Predicted 12-month customer LTV using Python + XGBoost and designed a Power BI dashboard for segment insights and marketing decisions.


## 🧰 Tech Stack

*Languages & Libraries*
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Jupyter Notebook

*Visualization*
- Power BI  
- Matplotlib / Seaborn (optional)

*Data*
- customers.csv  
- transactions.csv  
- Engineered RFM features  

---

## 🔧 Steps Performed

### 1️⃣ Data Preparation
- Cleaned missing values and standardized date formats.
- Merged customer and transaction data.
- Created snapshot date for recency calculation.
- Generated processed dataset: ltv_features_raw.csv.

### 2️⃣ Feature Engineering (RFM)
- *Recency:* Days since last purchase  
- *Frequency:* Number of orders  
- *Monetary (avg):* Average order value  
- Additional features: orders_90d, total spend

### 3️⃣ Model Training
- XGBoost Regressor  
- Train/test split  
- Evaluated using MAE & RMSE  
- Generated predictions → ltv_predictions.csv

### 4️⃣ Customer Segmentation
- High / Medium / Low value groups  
- Based on predicted LTV distribution  

### 5️⃣ Dashboards
- *Page 1:* Business KPIs, segment distribution, top customers  
- *Page 2:* Feature importance, RFM behavior insights  

---

## 📊 Power BI Dashboards

*Page 1 — Business Overview*  
- KPIs for total predicted LTV  
- Segment distribution  
- Donut chart for contribution  
- Top LTV customers  
- Behaviour filters  

*Page 2 — Behaviour & Model Insights*  
- Feature importance chart  
- LTV vs Frequency  
- LTV vs Recency  
- LTV vs Monetary scatter  
- Insights summary box  

---

## 📈 Results

- Identified high-value customers driving majority of revenue.
- Found that *frequency* and *average spend* are the strongest predictors of LTV.
- Inactive customers (high recency) show low predicted future value.
- Created clear segmentation for marketing and retention strategies.

---

## 📝 Business Recommendations

- Focus retention efforts on *High-LTV* customers.
- Upsell to *Medium-LTV* segment (highest growth potential).
- Re-engage inactive customers using personalized offers.
- Increase average order value through product bundling and discounts.

---


## 🤝 Contact

If you want to connect or need help:
*Somasekhar Kadiyam*  
Email: sekhar.kadiyam002@gmail.com  
LinkedIn: https://www.linkedin.com/in/soma-sekhar-kadiyam-842707321
