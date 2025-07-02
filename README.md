🧠 Customer Analytics & Campaign Prediction using XGBoost
This project analyzes sales and customer data from a retail company to generate actionable business insights and predict future customer behavior using advanced machine learning techniques. The main goals are customer segmentation, product and geographic analysis, and campaign targeting using XGBoost models.

🔍 Key Objectives
Segment customers based on spending behavior using K-Means clustering.

Identify top-performing countries and products based on historical sales data.

Analyze seasonal trends to uncover the best and worst quarters for sales.

Predict customer behavior using XGBoost:

Next purchase timing (regression)

Preferred product line (classification)

Preferred country (classification)

Generate data-driven marketing campaigns tailored to high-priority and high-value customers.

🚀 Machine Learning Models
XGBoost Regressor: Predicts the number of days until a customer's next purchase.

XGBoost Classifiers: Predict customers' likely product interests and target countries.

LabelEncoder + StandardScaler: Handle categorical and numerical preprocessing.

Data Augmentation: Ensures all classification labels are represented during training.

📊 Insights Generated
Identified high-value clusters of customers based on average order value and recency.

Found USA, Spain, and France as the top-performing countries.

Highlighted Classic Cars and Vintage Cars as the most profitable product lines.

Determined Q4 as the best-performing quarter, while Q2 is the weakest.

Created personalized campaign strategies, optimized by predicted next purchase dates.

📁 Outputs
campaign_recommendations.csv: Targeted marketing recommendations.

Trained models: Saved using joblib for reuse (next_purchase_model.pkl, etc.).

Visualizations: Insights into cluster profiles, sales trends, and recommendations (saved as PNGs).

🛠 Technologies Used
Python, Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn, XGBoost

Joblib (for model persistence)
