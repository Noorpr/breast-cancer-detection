# 🧪 Breast Cancer Dataset Analysis & Classification

This project presents a comprehensive exploration of the **Breast Cancer dataset** available in the `scikit-learn` library. The analysis includes data visualization, feature engineering, and classification model development using three popular algorithms.

## 📊 Visualizations

To gain insights into the distribution and relationships of features in the dataset, several visualizations were created:

- **Scatter Plot** – To observe relationships between pairs of features.
- **Histogram** – To examine the distribution of individual features.
- **Violin Plot** – To show the spread and density of the data across different classes.
- **Heatmap** – To visualize correlations between features.

## 🛠️ Feature Engineering

From the dataset, the **first 10 features** (mean-related) were selected. For each feature, the following engineered features were created:

- **Cumulative Sum**
- **Cumulative Minimum**
- **Cumulative Maximum**

These new features help the model better understand patterns in the data over feature positions.

## 🤖 Models Trained

Three classification models were trained and evaluated:

1. **K-Nearest Neighbors (KNN)**
2. **Decision Tree Classifier**
3. **Logistic Regression**

### ✅ Best Result

- **Model**: Logistic Regression
- **Accuracy**: **92%**

This indicates that logistic regression performed the best on the dataset among the three tested algorithms.

## 📚 Technologies Used

- Python
- scikit-learn
- pandas
- seaborn
- matplotlib