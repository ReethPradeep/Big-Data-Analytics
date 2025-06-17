
# 📊 Big Data Pipeline

## 📄 Project Overview
This project illustrates how to build a full-scale Big Data analytics pipeline to process and analyse stock market data with the help of such tools as Hadoop, Spark, Hive, and MLlib. The end objective is to extract valuable information and modelling to predict stock closing prices. The data ingestion, preprocessing, exploratory analysis, machine learning, and visualisation workflow are involved.

## 🔧 Key Features
- End-to-end Big Data pipeline using cloud (GCP) and open-source tools.
- Preprocessing and feature engineering on historical stock data.
- Predictive modelling using Random Forest and XGBoost.
- Performance evaluation with RMSE, MAE, and R² metrics.
- Visualisations for trend analysis and model comparison.

## 🖥️ Technologies Used
- Apache Hadoop
- Apache Spark & PySpark
- Apache Hive
- Google Cloud Platform (GCS, Dataproc)
- MLlib, XGBoost, Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook (Google Colab)

## 📁 Project Structure
```
├── dataset.csv                   # Stock market dataset (AAPL, GOOG, MSFT, NFLX)
├── big_data_analytics_pynb.ipynb  # Full notebook with pipeline, ML, and visualisations
├── README.md                     # Project documentation
```

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone <repository_url>
   ```

2. **Open Notebook**
   - Launch `big_data_analytics_pynb.ipynb` in Jupyter/Colab.
   - Upload or link the `dataset.csv`.
   - Run all cells sequentially for preprocessing, ML, and result visualisation.

## 📊 Results
- **Model Insights**: Random Forest outperformed XGBoost with lower RMSE and higher R².
- **Visualisations**: Provided insights into closing price trends, feature importance, and performance metrics.
- **Practical Use**: This pipeline can be adapted for real-time stock monitoring and predictive analytics in financial domains.



