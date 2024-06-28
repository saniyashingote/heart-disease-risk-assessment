# Heart Disease Risk Assessment

This project aims to build a user interface for inputting health metrics and develop a machine learning model to predict the risk of heart disease.

## Description

The project consists of two main parts:
1. **Data Preprocessing and Model Training**: This is done using a Jupyter Notebook where the dataset is preprocessed, and a Random Forest model is trained.
2. **User Interface**: A Streamlit app where users can input their health metrics and get a heart disease risk assessment based on the trained model.

## Technologies

- Python
- Jupyter Notebook
- Streamlit
- Scikit-Learn
- Pandas
- Joblib

## Setup

### Prerequisites

- Python 3.7 or above

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-risk-assessment.git
    cd heart-disease-risk-assessment
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
### Dataset

The dataset used is the UCI Heart Disease dataset. It can be downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).

### Data Preprocessing and Model Training

1. Open the Jupyter Notebook `preprocess.ipynb`.
2. Run the cells to preprocess the data and train the Random Forest model.
3. The trained model will be saved as `heart_disease_model.pkl`.

### User Interface

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. This will open the Streamlit app in your default web browser where you can input health metrics and get a heart disease risk assessment.
