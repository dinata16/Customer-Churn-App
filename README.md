# Unleashing the Power of Predictive Analytics: The Customer Churn Prediction App
![preview app](https://github.com/user-attachments/assets/b3941290-3229-43e9-aede-449ad5b30008)
## Introduction

In today's competitive market, retaining customers is more important than ever. The Customer Churn Prediction App empowers businesses to predict which customers are likely to leave, allowing them to take proactive measures to retain them. Built with the simplicity and interactivity of Streamlit, this app leverages machine learning to make accurate predictions based on the [Telco Customer Churn Dataset](https://www.kaggle.com/c/customer-churn-prediction-2020/overview).

## Project Overview

This project involves the development of a predictive model to foresee customer churn. Utilizing Random Forest, the model analyzes key features from the dataset to deliver accurate predictions. The project comprises:

- **churn_app.py**: The main file driving the Streamlit application.
- **model_pipeline_full.pkl**: The pre-trained machine learning model.
- **Data Test.csv**: A sample dataset to test the application.

## Getting Started

### Prerequisites

Before you begin, ensure you have Python installed on your machine. You’ll also need to install a few libraries:

```
pip install streamlit pandas scikit-learn
```
### Installation
1. Clone the repository and navigate to the project directory:
```
git clone <your-repository-url>
cd <repository-folder>
```

2. Install the requirements:
```
pip install -r requirements.txt
```

3. Run the application using Streamlit:
```
streamlit run churn_app.py
```
You should now see the app running at http://localhost:8501.

## Using the App
- Online:
You can input the requested information according to this app manually
- Batch File:
To get started, upload your dataset by clicking on the "Browse files" button. Ensure your file follows the format of the provided Data Test.csv.

## Making Predictions
You can simply hit the "Predict" button. The app will display result of predictions indicating the likelihood of each customer churning.

## Features of the App
- User-Friendly Interface: An intuitive design makes navigating the app a breeze.
- Real-Time Predictions: Receive instant results once the data is uploaded or you can input manually.

## The Model Behind the Magic
Our predictive model is built using Random Forest, a robust method for binary classification tasks. Trained on the Telco Customer Churn dataset, the model analyzes factors such as state, total charge, total minutes to predict churn.

## Example Dataset
Included in this repository is Data Test.csv, a sample dataset to help you get started. Feel free to use your own data, provided it follows the same structure.

## Contributing
We welcome contributions! If you have suggestions or improvements, fork the repository and create a pull request. Let's make this app even better together.

## License
This project is open-source and licensed under the MIT License. Check the LICENSE file for more information.

Thank you for exploring the [Customer Churn Prediction App](https://churncustomer.streamlit.app). Happy Predicting!