# Lung Cancer Prediction Model

This project predicts the likelihood of lung cancer using a machine learning model based on demographic, lifestyle, and health-related data.

## Features
- **Binary Classification**: Predicts lung cancer (Yes/No).
- **Key Attributes**: Gender, age, smoking habits, anxiety, chronic diseases, and symptoms like coughing and chest pain.
- **Model**: Random Forest Classifier for high accuracy and feature importance analysis.
- **Preprocessing**: Handles categorical encoding and normalization for optimized model performance.

## Technologies Used
- **Python Libraries**:
  - `pandas`, `numpy`: Data manipulation and numerical computations.
  - `scikit-learn`: Machine learning algorithms, preprocessing, and evaluation.
  - `matplotlib`, `seaborn`: Visualization.
  - `joblib`: Model saving and loading.

## Workflow
1. Data preprocessing: Encode, normalize, and split data.
2. Train a Random Forest Classifier.
3. Evaluate model using accuracy, classification report, and confusion matrix.
4. Save trained model for future predictions.
5. Test with sample inputs.

## Outputs
- Accuracy and classification metrics.
- Confusion matrix visualization.
- Feature importance bar chart.
- Saved model for future use.

## Future Work
- Incorporate additional features for improved accuracy.
- Deploy the model as a web or mobile application.

