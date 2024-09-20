# Breast Cancer Detection using Logistic Regression

## Project Overview
This project focuses on building a machine learning model to detect whether a tumor is **benign** or **malignant** using the **Breast Cancer Wisconsin Dataset**. The model employs **Logistic Regression**, which is a classification algorithm commonly used for binary classification tasks. The objective is to assist in early cancer detection, which is critical for treatment and survival rates.

## Dataset
The dataset used for this project is the **Breast Cancer Wisconsin Dataset**, available on [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data) or the UCI Machine Learning Repository. It includes 30 numerical features extracted from images of cell nuclei in breast cancer biopsies, along with a diagnosis label:
- `B` for benign
- `M` for malignant

### Features
- **Input Features**: 30 numeric features such as `radius_mean`, `texture_mean`, `perimeter_mean`, and others.
- **Target Variable**: `diagnosis` (0 = benign, 1 = malignant)


## Steps
1. **Data Preprocessing**:
    - Loaded and explored the dataset.
    - Dropped unnecessary columns.
    - Scaled the features using `StandardScaler` to ensure better model performance.
    
2. **Model Training**:
    - Used **Logistic Regression** to build a model for binary classification.
    - Split the data into training (80%) and testing (20%) sets.
    - Applied `StandardScaler` to normalize the features.

3. **Model Evaluation**:
    - Evaluated the model using accuracy, confusion matrix.
    - Visualized the model's performance using confusion matrix.
    
## Visualizations
The following visualizations were included to better understand the dataset and model performance:
1.  **Confusion Matrix**: Visualizes the accuracy of the classification.

![image](https://github.com/user-attachments/assets/d027e628-f9e6-4320-9547-3615d709fd80)


2. **CounterPlot**


![image](https://github.com/user-attachments/assets/8a21047a-94ea-42dc-8431-f3be9c4eeb6b)



### Prerequisites
Make sure you have Python and the following libraries installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## Results
- The model achieved an accuracy of **96.49%** on the test set.

## Conclusion
This project demonstrates the application of **Logistic Regression** to a healthcare problem. By building a robust model, we aim to assist in the early detection of breast cancer, which can lead to better patient outcomes. Future improvements could include using other classification algorithms like Random Forest or Support Vector Machines to further enhance performance.


