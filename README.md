# Diabetes Progression Prediction

## Objective
This project aims to model the progression of diabetes using the available independent variables from the Diabetes dataset in the sklearn library. The model will help healthcare professionals understand how different factors influence the progression of diabetes and potentially aid in designing better treatment plans and preventive measures.

## Dataset
The Diabetes dataset is used in this project, which is available in the sklearn library.

## Key Components

### 1. Loading and Preprocessing 
- Load the Diabetes dataset from sklearn.
- Handle any missing values if present.
- Normalize the features to ensure better performance of the ANN model.

### 2. Exploratory Data Analysis (EDA) 
- Perform EDA to understand the distribution of features and the target variable.
- Visualize the relationships between features and the target variable.

### 3. Building the ANN Model 
- Design a simple ANN architecture with at least one hidden layer.
- Use appropriate activation functions.

### 4. Training the ANN Model 
- Split the dataset into training and testing sets.
- Train the model on the training data.
- Use an appropriate loss function and optimizer.

### 5. Evaluating the Model 
- Evaluate the model on the testing data.
- Reporting performance metrics such as Mean Squared Error (MSE) and R² Score.

### 6. Improving the Model 
- Experiment with different architectures, activation functions, or hyperparameters to improve the model performance.
- Report the changes made and the corresponding improvement in performance.

## Results
- **Original Model Performance:**
  - Mean Squared Error: 2940.25
  - R² Score: 0.445

- **Improved Model Performance:**
  - Mean Squared Error: 2783.50
  - R² Score: 0.475

## Conclusion
The improved model with increased neurons and an additional hidden layer showed better performance in predicting the progression of diabetes. The Mean Squared Error decreased, and the R² Score increased, indicating a better fit and more explained variance.
