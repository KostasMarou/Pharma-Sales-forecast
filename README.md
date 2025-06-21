# Pharma Sales Forecasting 📈💊

This project demonstrates time-series forecasting of monthly pharmaceutical drug sales using Python, Azure Machine Learning, and Prophet (Meta/Facebook). It showcases cloud-first modeling, visualization, and deployment readiness for real-world business use.

---

## 🔍 Project Summary

- **Objective:** Predict future sales of high-volume drug category **N02BE** (pain relief) using historical data (2014–2019)
- **Tools Used:** Azure Machine Learning Studio, Python, Prophet, matplotlib, ARIMA (for benchmarking)
- **Result:** 12-month forecast with holidays, trends, and seasonality integrated

---

## 💡 Key Highlights

- 📊 **Visualized** long-term sales trends and patterns  
- 🧠 **Trained a Prophet model** with Danish holidays and seasonal effects  
- 🔁 **Benchmarked with ARIMA** to show Prophet’s superiority on this dataset  
- 💾 **Saved model (.pkl)** for use in Docker and web apps (Flask)  
- ☁️ **Built entirely using Azure free-tier services**

---

## 📂 Project Structure

pharma-forecasting/
├── notebooks/ # Azure ML notebook
│ └── pharma_forecasting.ipynb
├── model/
│ └── prophet_n02be_model.pkl
├── images/
│ └── forecast_prophet.png
│ └── forecast_arima.png
│ └── sales_trends.png
└── README.md
