# donation_prediction
Predicting donation likelihood using H2O's neural networks and random forest in R
Achieved **AUC: 0.5204** on test data.

## Features
- Data preprocessing: Handling class imbalance (`ROSE`), scaling, dummy encoding
- Hyperparameter tuning: Grid search for optimal NN and RF parameters
- Model evaluation: ROC curves, confusion matrices, variable importance

## Code Structure
This project uses a single script (`donation_prediction.R`) that covers:  
1. **Data Preprocessing**: Handling class imbalance, scaling, and feature engineering.  
2. **Model Training**: Neural networks and random forests with H2O (including hyperparameter tuning).  
3. **Evaluation**: ROC curves, confusion matrices, and performance metrics.  

Note: For improved modularity, future work will split this into separate scripts (preprocessing, training, evaluation).*  

## How to Run
1. Install dependencies:  
   ```r
   install.packages(c("here", "h2o", "dplyr", "caret", "pROC", "ROSE", "recipes"))
