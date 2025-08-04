
# 🚢 Titanic Dataset: Preprocessing & Visualization
This project demonstrates how to clean, preprocess, and visualize the iconic Titanic dataset using Python. The primary goal is to enhance data quality and uncover patterns related to passenger survival—laying the groundwork for future machine learning applications.

# 📌 Project Highlights
📥 Data Import & Exploration
Loaded the dataset using pandas for structured data handling.

Explored dataset structure with .head(), .info(), and .shape() to understand dimensions and types.

# 🔍 Handling Missing Data
Addressed missing values in numerical features (e.g., Age) using KNNImputer from sklearn.impute.

Verified data integrity before and after imputation to ensure completeness.

# 🔢 Feature Transformation
Transformed categorical columns like Sex into numeric format using LabelEncoder.

Applied StandardScaler to normalize numerical variables such as Age and Fare for better model compatibility.

# 📊 Exploratory Data Visualization
Utilized Seaborn and Matplotlib for visual storytelling.

Generated box plots to spot outliers and understand variable distributions.

Applied Interquartile Range (IQR) method with whisker logic to treat skewed data in features like Age, Fare, and SibSp.

# 🧹 Outlier Management
Created a custom Python function to cap extreme values outside the IQR thresholds.

Mitigated the influence of outliers without removing valuable data points.

# 🧰 Tools & Technologies
Python 3.x

pandas, numpy – Data manipulation

seaborn, matplotlib – Visualization

scikit-learn – Imputation, encoding, and scaling(KNNImputer, LabelEncoder, StandardScaler)

# ✅ Project Outcome
A fully preprocessed and visualized Titanic dataset, optimized for further analysis or machine learning. This workflow improves data quality, reduces noise, and prepares the dataset for impactful insights and predictions.
