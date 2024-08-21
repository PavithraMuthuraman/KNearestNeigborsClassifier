# K-Nearest Neighbors
*K-Nearest Neighbors Classification for Predicting Ad Purchases in Social Network Data*

**Description:** This project focuses on predicting whether a customer will purchase a product based on their gender, age, and estimated salary using the K-Nearest Neighbors (KNN) algorithm. The "Social Network Ads" dataset is utilized, which contains various user features and information on whether they made a purchase.

## Project Overview:
- **Objective:** Predict the likelihood of a customer purchasing a product based on their characteristics using the KNN model.
- **Model:** K-Nearest Neighbors is employed to classify customer data into purchase or no-purchase categories.
- **Dataset:** The dataset includes user features such as gender, age, and estimated salary, along with the target variable indicating whether they purchased the product.

## Files Included:
- `Social_Network_Ads.csv:` The dataset used for training and testing the KNN model.
- `KNeighborsClassifier.ipynb:` The Python script that performs data preprocessing, model training, and prediction.

## Code Execution:
1. **Setup Environment:** Install the required libraries (`numpy`, `pandas`, `scikit-learn`).
2. **Data Loading:** Place `Social_Network_Ads.csv` in the appropriate directory, then load and inspect the dataset.
3. **Preprocessing:** Remove unnecessary columns, encode categorical data, and divide the dataset into dependent and independent variables.
4. **Model Training:** Split the dataset into training and testing sets, then execute the script to train the KNN model on the training data.
5. **Prediction:** Predict customer purchase behavior for test data.
6. **Customize Input:** Add custom data to the script to test predictions for different customers.
