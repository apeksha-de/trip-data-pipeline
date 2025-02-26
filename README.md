# 🚖 Trip Data Pipeline

This project processes NYC taxi trip data using PySpark.

## 📂 Dataset
- **File Used:** `yellow_tripdata_example.csv`
- **Source:** NYC Open Data

## ⚙️ Technologies Used
- **PySpark** for data transformation
- **Google Colab** for execution
- **Git & GitHub** for version control

## 🚀 How to Run
1. Upload `yellow_tripdata_example.csv` to Google Colab.
2. Use the script to load and transform data:
   ```python
   df = spark.read.option("header", True).csv("/content/yellow_tripdata_example.csv")
   df.show(5)
# trip-data-pipeline
