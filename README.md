# 🌬️ German Renewable Energy Forecasting Using Machine Learning

This project uses machine learning to forecast wind energy generation, predict shortfalls, and detect anomalies in Germany's renewable power grid. Built as part of the ADTA 5340 course at the University of North Texas, the models leverage 15-minute interval data from 2015–2018 to support smarter energy planning and grid reliability.

---

## 📁 Files Included

- `German_Renewable_Energy.ipynb` – Jupyter Notebook with full code, analysis, and model implementation
- `5340_Project_Report.docx` – Formal report explaining methodology, models, results (APA formatted)
- `ADTA_5340_Group7_PPT.pptx` – Final presentation summarizing the project

---

## 💡 Project Goals

1. Predict next-day wind energy generation using historical and time-based features
2. Detect shortfalls in renewable supply before they impact operations
3. Identify anomalies and outliers in wind generation patterns

---

## 🧠 Models Used

- **Random Forest Regressor** – Forecast next-day wind generation
- **Random Forest Classifier** – Predict shortfall events
- **DBSCAN Clustering** – Detect anomalies in energy patterns

---

## 📊 Performance Highlights

| Task                        | Model                  | Metric       | Value   |
|-----------------------------|------------------------|--------------|---------|
| Wind Generation Forecasting | Random Forest Regressor | MAE          | 1.64    |
| Wind Generation Forecasting | Random Forest Regressor | RMSE         | 2.58    |
| Shortfall Prediction        | Random Forest Classifier| F1 Score     | 0.75    |
| Anomaly Detection           | DBSCAN                  | Outliers Detected | 16   |

---

## 📈 Visualizations

- Wind vs Solar trends over time
- Actual vs Predicted wind generation plots
- Confusion matrix for shortfall detection
- DBSCAN cluster plots for anomaly identification

---

## 🔧 Tech Stack

- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- CRISP-DM methodology
- Microsoft Word & PowerPoint (for documentation and presentation)

---

## 🏁 Future Work

- Integrate real-time weather data for enhanced forecasting
- Deploy model using real-time pipelines (e.g., AWS/GCP)
- Improve recall for shortfall detection model
- Build dashboards for anomaly monitoring

---

## 📚 Authors

Team 7 – ADTA 5340 Spring 2025  
- Varun Kumar Atkuri  
- Irfan Ahmed Shaik  
- Manasa Dontireddy  
- Prudhvi Kolli  
- Shree Sai Charan Rekala  

---

> 📌 Developed as a final project at the University of North Texas (UNT)
