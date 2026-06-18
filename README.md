<h1 align="center">🛒 E-Commerce Order Analytics & Order Status Prediction</h1>

<p align="center">
Data Analysis and Machine Learning project for understanding customer behavior, sales trends, and predicting order status using Random Forest Classifier.
</p>

---

## 📖 Overview

This project performs Exploratory Data Analysis (EDA) on an e-commerce dataset and builds a machine learning model to predict order status.

The project includes:

- Data cleaning
- Missing value handling
- Feature engineering
- Visualization and trend analysis
- Customer insights
- Sales analysis
- Order status prediction using Random Forest

---

## 🚀 Features

✔ Data preprocessing

✔ Missing value treatment

✔ Duplicate detection

✔ Date feature extraction

✔ Product-wise revenue analysis

✔ Payment method analysis

✔ Coupon usage analysis

✔ Correlation heatmap

✔ Random Forest Classification

✔ Order status prediction

✔ Confusion matrix visualization

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📂 Dataset Features

The dataset contains:

- OrderID
- CustomerID
- Date
- Product
- Quantity
- UnitPrice
- ShippingAddress
- PaymentMethod
- TrackingNumber
- ItemsInCart
- CouponCode
- ReferralSource
- TotalPrice
- OrderStatus

---

## ⚙️ Workflow

### 1. Data Loading

```python
pd.read_csv()
```

---

### 2. Data Cleaning

- Checked missing values
- Filled missing CouponCode values
- Removed unnecessary duplicates

---

### 3. Feature Engineering

Extracted:

- Weekday
- Month
- Year

from Date column.

---

### 4. Exploratory Data Analysis

Visualizations created:

- Product distribution
- Revenue by product
- Monthly order count
- Payment method distribution
- Coupon usage
- Quantity distribution
- Total price boxplot
- Items in cart vs Total price
- Correlation heatmap
- Referral source analysis

---

### 5. Machine Learning

Target variable:

```
OrderStatus
```

Model Used:

```
Random Forest Classifier
```

Pipeline:

```
One Hot Encoding
↓
Random Forest
```

---

### 6. Model Evaluation

Metrics used:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📊 Visualizations

- Countplot
- Barplot
- Histogram
- Scatterplot
- Boxplot
- Heatmap

---

## 📁 Project Structure

```
├── Dataset for Data Analytics - Sheet1.csv
├── PROJECT1.ipynb
├── README.md
└── requirements.txt
```

---

## 📦 Installation

Clone repository:

```bash
git clone https://github.com/yourusername/Ecommerce-Order-Analytics.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run:

```bash
jupyter notebook
```

Open:

```
PROJECT1.ipynb
```

---

## 🎯 Future Improvements

- XGBoost implementation
- Customer segmentation
- Sales forecasting
- Streamlit dashboard
- Deployment using Flask
- Recommendation system

---

## 👩‍💻 Author

### Khyati Sahu

- Data Science Enthusiast
- Python Developer
- Machine Learning Learner

---

⭐ If you found this project useful, consider giving it a star.
