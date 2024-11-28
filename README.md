
# Breast Cancer Prediction Using Decision Tree Classifier

This project predicts whether breast cancer is benign or malignant using a **Decision Tree Classifier**. It processes a breast cancer dataset, evaluates model performance using metrics such as precision, recall, and F1-score, and visualizes the decision tree and feature importance.

## Features

- **Data Preprocessing**:
  - Extracts features and target variables from the dataset.
  - Splits the data into training and testing subsets.
- **Model Building**:
  - Trains a Decision Tree Classifier with specified hyperparameters.
- **Performance Evaluation**:
  - Provides a detailed classification report.
  - Visualizes the decision tree and ranks features by importance.

## Dataset

The dataset is sourced from `breast-cancer.csv`. It includes diagnostic information (`diagnosis`) and multiple features extracted from breast cancer cell nuclei images.

### Example Data

| ID        | Radius | Texture | ... | Diagnosis |
|-----------|--------|---------|-----|-----------|
| 842302    | 17.99  | 10.38   | ... | Malignant |
| 842517    | 20.57  | 17.77   | ... | Malignant |
| 84300903  | 19.69  | 21.25   | ... | Benign    |

- **Diagnosis**: Target variable with classes:
  - `M`: Malignant
  - `B`: Benign

## Technologies Used

- **Python**: Programming language.
- **Pandas**: For data manipulation.
- **NumPy**: For numerical computations.
- **scikit-learn**: 
  - `DecisionTreeClassifier` for classification.
  - Tools for preprocessing, model evaluation, and visualization.
- **Matplotlib**: For plotting visualizations.
