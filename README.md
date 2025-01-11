# **Airbnb Price Prediction using Machine Learning: A Comprehensive Analysis and Model Selection**

### **Project Overview**
This project focuses on predicting the logarithm of Airbnb rental prices using various machine learning techniques. The goal is to create a robust predictive model that estimates Airbnb prices based on factors like location, property type, amenities, and other relevant features.

---

### **Objectives & Steps**
1. **Understanding the Data**: 
   - Visualize the dataset, explore its structure, data types, and identify missing values or anomalies.
   - Clean the data by handling missing values and ensuring the correct data types for each feature.

2. **Feature Engineering**:
   - Convert categorical variables into numerical formats using **One-Hot Encoding** and apply **TF-IDF Vectorization** for text-based features like the 'name' and 'description' of listings.

3. **Correlation Analysis and PCA**:
   - Identify key features that are most influential in predicting **log_price**.
   - Use **Principal Component Analysis (PCA)** to reduce dimensionality and retain the most relevant features.

4. **Model Development & Evaluation**:
   - Train and evaluate various machine learning models, including **linear models**, **decision trees**, **random forests**, **gradient boosting**, and **ensemble methods** like **StackingRegressor**.
   - Evaluate models using metrics such as **R²** and **Mean Squared Error (MSE)** to assess their performance.

5. **Model Selection**:
   - Compare the models based on their training and test performance to select the best model that avoids overfitting and provides reliable price predictions.

---

### **Files Included**
1. **airbnb_train.csv**: The training dataset containing Airbnb listings and their features.
2. **airbnb_test.csv**: The test dataset used for final model predictions.
3. **Predictions_log_price.csv**: The file containing the predictions of log prices after the best-performing model is selected.

---

### **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### **Contact**
For any questions or feedback, feel free to reach out to me via email or LinkedIn:
- **Email**: [ahmed.mili@edu.devinci.fr](mailto:ahmed.mili@edu.devinci.fr)
- **LinkedIn**: [Ahmed Mili](https://www.linkedin.com/in/ahmedmili/)
