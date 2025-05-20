
# 🚦 Big Data Analytics in Intelligent Transportation Systems

This project focuses on analyzing road traffic data using Apache Spark and machine learning techniques. It enables traffic prediction and analysis through Decision Tree and Linear Regression algorithms, uses PCA for dimensionality reduction, and compares model performance using RMSE.

---

## 📌 Description

The system demonstrates how big data tools can be used to process transportation datasets efficiently. It supports:

- Data upload and preprocessing using PySpark
- Application of Decision Tree and Linear Regression models
- Dimensionality reduction using Principal Component Analysis (PCA)
- Accuracy comparison between models using RMSE metric
- Graphical output to visualize performance

---

## 📁 Folder Structure

```
big-data-traffic-analytics/
├── data/
│   └── sample_traffic_data.csv           # Input dataset
├── src/
│   ├── spark_session.py                  # Spark session setup
│   ├── decision_tree.py                  # Decision Tree logic
│   ├── linear_regression.py              # Linear Regression logic
│   ├── pca_feature_selection.py          # PCA implementation
│   └── main.py                           # Main controller script
├── outputs/
│   └── accuracy_comparison.png           # Output RMSE comparison chart
├── requirements.txt                      # Python package dependencies
├── README.md                             # Project description
└── run.sh                                # Optional run script
```

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/big-data-traffic-analytics.git
cd big-data-traffic-analytics
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

Make sure Java and Apache Spark are correctly installed and configured.

### 3. Run the Project

```bash
python src/main.py
```

### 4. View Output

Check the `outputs/accuracy_comparison.png` file to see a comparison graph of model RMSE scores.

---

## 📄 Sample Dataset Format

```csv
feature1,feature2,feature3,target
45,67,23,1
56,45,12,0
67,34,34,1
50,50,30,0
60,60,20,1
```

---

## 🔧 Tools & Technologies

- Python 3.8+
- Apache Spark
- PySpark
- Matplotlib
- Pandas

---

## 📈 Output Example

![Output Graph](outputs/accuracy_comparison.png)

---

## 📜 License

This project is licensed under the MIT License - feel free to use and modify.

---

## 🙋 Author

**Your Name**  
GitHub: [@yourusername](https://github.com/yourusername)
