# Credit Score Prediction Project 💳📊

## Overview
This project aims to predict credit scores (categorized as 'Good', 'Standard', and 'Poor') using machine learning techniques. The entire ML pipeline includes data extraction, cleaning, preprocessing, model training, feature selection, dimensionality reduction, and deployment using Streamlit. The project applies Mutual Information for feature selection and Principal Component Analysis (PCA) for dimensionality reduction.

Project link: [Credit_Score_Prediction](https://credit-score-prediction.streamlit.app/)

## Table of Contents
- [Getting Started 🚀](#getting-started-)
- [Prerequisites 📋](#prerequisites-)
- [Data Extraction & Cleaning 🧹](#data-extraction--cleaning-)
- [Data Preprocessing 📝](#data-preprocessing-)
- [Feature Selection Using Mutual Information 📊](#feature-selection-using-mutual-information-)
- [Dimensionality Reduction with PCA 📉](#dimensionality-reduction-with-pca-)
- [Model Training 🏋️‍♂️](#model-training-)
- [Model Evaluation 📈](#model-evaluation-)
  - [Classification Report 📋](#classification-report-)
  - [Confusion Matrix 🔢](#confusion-matrix-)
  - [ROC and AUC Curve 📊](#roc-and-auc-curve-)
- [Pipeline Integration 🔗](#pipeline-integration-)
- [Model Deployment on Streamlit 🌐](#model-deployment-on-streamlit-)
- [Real World Examples 🌍](#real-world-examples-)
- [Results 🏆](#results-)
- [Contributing 🤝](#contributing-)
- [License 📄](#license-)
- [Acknowledgments 🙏](#acknowledgments-)

## Getting Started 🚀
Follow these instructions to set up and run the project locally for development and testing purposes.

## Prerequisites 📋
Ensure that you have Python installed along with the required libraries. Download Python from [python.org](https://www.python.org/) and install the libraries using pip.

## Data Extraction & Cleaning 🧹
The dataset used for this project is stored in the `data` directory. The primary data file is `credit_score_data.csv`, which contains features such as `Annual_Income`, `Monthly_Inhand_Salary`, `Interest_Rate`, and others relevant to predicting credit scores.

### Data Extraction:
- Data is loaded from CSV files using Pandas.
- Initial exploration is conducted to understand the data's structure and contents.

### Data Cleaning:
- Missing values are handled using imputation techniques.
- Outliers are detected and treated.
- Irrelevant features are removed to streamline the dataset.

## Data Preprocessing 📝
The preprocessing steps involve scaling numerical features, encoding categorical variables, and splitting the dataset into training and test sets.

### Scaling:
- Standardization is applied to numerical features to ensure all features contribute equally to the model.

### Encoding:
- Categorical variables are converted into numerical form using techniques like one-hot encoding.

### Splitting the Data:
- The dataset is split into training and testing sets using an 80-20 ratio.

## Feature Selection Using Mutual Information 📊
Feature selection is performed using Mutual Information to identify the most relevant features for predicting credit scores.

### Mutual Information:
- Measures the dependency between each feature and the target variable.
- Helps in selecting features that provide the most information about the target.

### Visualization:
- **Top Features**: Bar plot showcasing features with the highest mutual information scores.

## Dimensionality Reduction with PCA 📉
Principal Component Analysis (PCA) is used to reduce the dimensionality of the feature space while retaining the most important information.

### PCA:
- Reduces the number of features by transforming them into a new set of uncorrelated features (principal components).
- Helps in speeding up the model training process and reducing overfitting.

### Visualization:
- **PCA Components**: Scree plot to visualize the explained variance by each principal component.

## Model Training 🏋️‍♂️
The model training process involves using algorithms like logistic regression, decision tree, and random forest to learn from the preprocessed data.

### Logistic Regression:
- A linear model used for classification tasks.
- Suitable for binary and multi-class classification.

### Decision Tree:
- A tree-based model that splits data based on feature values.
- Provides easy interpretability.

### Random Forest:
- An ensemble method that aggregates multiple decision trees.
- Increases accuracy and robustness.

## Model Evaluation 📈
The models are evaluated using various metrics, including accuracy, precision, recall, and F1-score.

### Classification Report 📋
- Provides detailed performance metrics for each class (Good, Standard, Poor).

### Confusion Matrix 🔢
- A matrix showing the actual vs. predicted classifications.
- Helps in understanding model errors.

### ROC and AUC Curve 📊
- **ROC (Receiver Operating Characteristic)** curve plots the true positive rate against the false positive rate.
- **AUC (Area Under the Curve)** measures the model's ability to distinguish between classes.

## Pipeline Integration 🔗
- The entire ML pipeline from data extraction to model training and evaluation is integrated for streamlined processing.

## Model Deployment on Streamlit 🌐
- The trained model is deployed using Streamlit for easy access and interaction.
- Users can input new data and obtain credit score predictions in real-time.

## Real World Examples 🌍
- Examples include predicting credit scores for various profiles to illustrate the model's real-world applicability.

## Results 🏆
- The final trained models are saved and can be used to classify new instances of credit scores.

## Contributing 🤝
- Contributions are welcome! Please feel free to fork the repository, make your changes, and create a pull request.

## License 📄
- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.

## Acknowledgments 🙏
- Special thanks to data providers and open-source contributors who helped make this project possible.
