# **Predicting Airbnb Prices using Machine Learning**

### **Project Overview**
This project is focused on predicting the logarithm of Airbnb rental prices using various machine learning techniques. The goal is to create a robust predictive model that can estimate Airbnb prices based on various factors such as location, property type, amenities, and other relevant features.

---

### **Objectives**
1. **Data Exploration and Cleaning**: 
   - Visualize and understand the data.
   - Clean the data by handling missing values and removing anomalies.

2. **Feature Engineering**:
   - Convert categorical variables into numerical formats using techniques like **One-Hot Encoding**.
   - Apply **TF-IDF Vectorization** to handle text-based features such as the 'name' and 'description' of listings.

3. **Correlation Analysis and PCA**:
   - Identify key features for price prediction and reduce dimensionality using **Principal Component Analysis (PCA)**.

4. **Model Development**:
   - Develop, train, and evaluate different machine learning models, including linear and non-linear models.

5. **Model Evaluation**:
   - Evaluate the model's performance using metrics like **R²** and **Mean Squared Error (MSE)**.

6. **Model Selection**:
   - Select the best-performing model based on evaluation metrics to predict Airbnb prices.

---

### **Project Steps**
1. **Understanding the Data**:
   - Visualize the dataset to understand its structure, types of data and the missing values.
  

2. **Data Cleaning**:
   - Handle missing values appropriately.
   - Remove outliers or anomalies.
   - Ensure correct data types for each feature.

3. **Feature Transformation**:
   - Use **One-Hot Encoding** to convert categorical variables (e.g., room type, cancellation policy) into numerical formats.
   - Standardize numerical features to bring them to a similar scale, which improves model performance.

4. **Correlation Analysis and PCA**:
   - Analyze correlations between features and the target variable (**log_price**).
   - Apply **PCA** to retain the most important features and reduce dimensionality.

5. **Modeling**:
   - Implement various machine learning models:
     - **Linear models** (e.g., ElasticNet, LinearSVR)
     - **Decision Trees** and **Random Forests**
     - **Gradient Boosting models** (e.g., GradientBoostingRegressor, HistGradientBoostingRegressor)
     - **Ensemble models** like **StackingRegressor**.

6. **Model Evaluation**:
   - Evaluate models using **R²** and **Mean Squared Error (MSE)** on both training and test data.
   - Compare the models based on their ability to generalize and predict accurately.

7. **Selecting the Best Model**:
   - After evaluation, select the best-performing model, which balances training and test performance to avoid overfitting.

---

### **Files Included**
1. **airbnb_train.csv**: The training dataset containing Airbnb listings and their features.
2. **airbnb_test.csv**: The test dataset on which the final model predictions are made.
3. **Predictions_log_price.csv**: The file containing the predictions of log prices after selecting the best-performing model.


---

### **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### **Contact**
For any questions or feedback, feel free to reach out to me via email or LinkedIn:

- **Email**: [ahmed.mili@edu.devinci.fr](mailto:ahmed.mili@edu.devinci.fr)
- **LinkedIn**: [Ahmed Mili](https://www.linkedin.com/in/ahmedmili/)

---
