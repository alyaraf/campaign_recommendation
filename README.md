# 🧠 Customer Analytics & Campaign Prediction using XGBoost

This project leverages machine learning and data analytics to generate customer insights and personalized campaign recommendations from retail sales data. It uses clustering, regression, and classification models to guide data-driven marketing strategies.

## 📌 Project Goals

- Segment customers based on purchasing behavior
- Identify high-value and high-frequency clients
- Predict:
  - Time to next purchase (regression)
  - Preferred product line (classification)
  - Preferred country (classification)
- Recommend optimized campaign timing and targeting

---

## 🔍 Key Insights

- **Top Countries**: Spain, France, Australia, UK, Italy
- **Underperforming Countries**: Singapore, Belgium, Switzerland
- **Top Product Lines**: Classic Cars, Vintage Cars, Motorcycles
- **Underperforming Product Lines**: Planes, Ships, Trains
- **Best Quarter**: Q4
- **Weakest Quarter**: Q2
- **High-value customers**: Clustered based on total spending, order frequency, and recency

---

## 📊 Visualizations

Key visualizations include:
- Customer clusters (KMeans)
- Monthly and quarterly sales trends
- Product and country performance
- Campaign targeting breakdown (priority & value)
  
Visuals are saved as:
- `purchase_timing_distribution.png`
- `product_recommendations.png`
- `country_recommendations.png`
- `customer_segments.png`

---

## 🚀 Machine Learning Models

| Task                         | Model           |
|------------------------------|-----------------|
| Time to next purchase        | `XGBRegressor`  |
| Predict preferred product    | `XGBClassifier` |
| Predict preferred country    | `XGBClassifier` |

Preprocessing steps:
- Categorical Encoding: `LabelEncoder`
- Feature Scaling: `StandardScaler`
- Missing label handling: Class balancing using data augmentation
