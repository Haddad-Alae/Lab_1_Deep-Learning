## Objective
This project demonstrates the use of PyTorch for handling regression and multi-class classification tasks as part of a deep learning lab exercise. The goal is to implement DNN/MLP architectures, tune hyperparameters, apply regularization techniques, and evaluate model performance.

## Project Structure
- **Part 1: Regression** .
- **Part 2: Multi-Class Classification** .

## Steps
### Part 1: Regression
- Data Exploration: Visualization and correlation analysis.
- Model Architecture: Implemented a DNN for regression.
- Hyperparameter Tuning: Used GridSearch to find optimal hyperparameters.
- Evaluation: Visualized loss and accuracy over epochs.

### Part 2: Classification
- Data Preprocessing: Cleaning, normalization, and augmentation.
- Model Architecture: Implemented a DNN for classification.
- Hyperparameter Tuning: Used GridSearch for hyperparameters.
- Evaluation: Analyzed metrics like accuracy, sensitivity, and F1-score.

## Results
•  Dropout Regularization is reducing overfitting but may have been applied too aggressively, leading to underfitting.
•  The model with no dropout performs better on the test data (lower test loss) but suffers from overfitting.

Without Regularization:
•	The model performs better on the training set, showing higher accuracy and F1 score. However, the test performance is not as good, indicating the model is overfitting.
•  With Regularization:
•	The model shows lower performance on both training and test sets, indicating it has been overly constrained by the regularization methods. However, it generalizes better to unseen data, as shown by the decrease in the overfitting gap (the difference between training and test performance).


## Learned Outcomes
This lab provided experience with:
- Implementing deep learning models for regression and classification.
- Performing EDA, data augmentation, and model evaluation.
- Using GridSearch for hyperparameter optimization.
