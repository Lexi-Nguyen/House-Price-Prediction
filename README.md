## 🏠 House Price Prediction

**Built with:** Python · Jupyter Notebook (.ipynb) · pandas · NumPy · scikit-learn

---

### ✨ Project Overview
This project focuses on predicting house prices using a real-world dataset of approximately **20,000 residential property sales** in the United States. The aim is to understand which factors influence housing prices and to build predictive models that can estimate sale prices based on property characteristics.

The project combines exploratory data analysis with machine learning techniques to compare different modelling approaches and identify the most effective one.

![Image](https://github.com/user-attachments/assets/5ecd28cd-54db-47b7-8914-867a7998d864)

---

### 📊 Dataset Description
The dataset contains a mix of numerical and categorical variables describing different aspects of residential properties, including structural features, location-related attributes, and property conditions. These features provide a broad view of the factors that may impact house prices.

View Dataset: [here](https://github.com/Lexi-Nguyen/House-Price-Prediction/blob/6d9caaf015cd5c62a2f4a77ac7624a19d631399f/house_price.csv)

---

### 🧹 Data Preparation & Exploration
- Cleaned the dataset and handled missing values  
- Selected relevant features for modelling  
- Applied **Min-Max scaling** to normalise numerical variables  
- Performed exploratory analysis to identify trends and relationships between features and house prices  
- Split the dataset into **70% training** and **30% validation** sets  

View Analysis: [here](https://github.com/Lexi-Nguyen/House-Price-Prediction/blob/a0e7f590115a9a36c3f34cf13306809be33fb240/House%20Price%20Prediction.ipynb)

---

### 🤖 Models Implemented
The following models were developed and compared:
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Multi-Layer Perceptron (MLP) Regressor with different hidden layer configurations  

---

### 📈 Model Evaluation
Model performance was evaluated using:
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R-squared (R²)  

The **MLP Regressor with two hidden layers (128, 64)** achieved the best overall performance, producing the lowest prediction error and demonstrating strong ability to capture complex patterns in housing data.

<img width="527" height="670" alt="Image" src="https://github.com/user-attachments/assets/1a8c6c99-b0a4-4a07-824c-35a6be0dd8b5" />

---

### 🔍 Key Insights
- House prices are influenced by multiple factors rather than a single feature  
- Models that can learn non-linear relationships perform better than simpler approaches  
- Proper data preparation and feature scaling significantly improve model performance  

---

### 💡 Business Value
This project demonstrates how predictive analytics can support:
- Property valuation and pricing strategies  
- Real estate investment analysis  
- Data-driven decision-making in housing markets  

---

### 📁 Repository Contents
- `House_Price_Prediction.ipynb` - complete data analysis and model development  
- `house_price.csv` - dataset  





