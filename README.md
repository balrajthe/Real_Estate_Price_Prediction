
# Real Estate Price Prediction Project

<p align="center">
<img src="https://img.freepik.com/premium-vector/urban-landscape-with-high-skyscrapers-subway_126283-690.jpg?w=1380" height="100px">
</p>

> [!IMPORTANT]
>
> **Disclaimer:** I used 99acres.com data in this project and I used those data for educational purposes only.

## Features
### •	Price Prediction Page: 
  Users can input different property features (like Property type, bedrooms, balconies, etc) and hit the Predict button to get the estimated price.
  
### •	The Analytics Page :
  This page shows some interesting insights regarding the Real Estate of the City (Gurgaon).
  
### •	Recommendation Page 
  In this page, we will get nearby properties within a selected area and radius. Second properties will be recommended based on the selected property.

  ## Tech Stack

|                 Tech | Stack                       |
| -------------------: | :-------------------------- |
| Programming Language | Python                      |
|      Version Control | Git & GitHub                |
|        Data Analysis | Pandas, Numpy               |
|        Visualization | Matplotlib, Seaborn, Plotly |
|     Machine Learning | Scikit-Learn                |
|   Frontend & Backend | Streamlit                   |
|           Deployment | AWS EC2                     |


## Problem Definition
This project aims to predict real estate prices by analyzing various property features and market conditions. The goal is to develop a model that can accurately estimate the price of a property based on its attributes.

## Data Collection
Data was scraped from a real estate website ([99acres](https://www.99acres.com)), including features such as location, size, number of bedrooms and bathrooms, amenities, and other relevant property details.

## Data Exploration and Analysis
Extensive Exploratory Data Analysis (EDA) was performed to understand the dataset. This included identifying patterns, trends, and correlations between property features and prices, and visualizing these relationships using plots and graphs.

## Data Preprocessing
The data was cleaned to handle missing values, outliers, and duplicates. Categorical variables were encoded, and numerical features were standardized. The dataset was split into training, validation, and test sets to ensure robust model evaluation.

## Feature Engineering
New features were created to capture more information about properties. For example, proximity to amenities, neighborhood quality, and historical price trends were derived.

## Model Selection
First, we selected a Baseline model to assess raw performance of the model on the pre-processed data. Then, various machine learning algorithms were considered, including linear regression, decision trees, random forests, gradient boosting, XGBoost, etc. The choice of algorithms was guided by their suitability for regression tasks.

## Model Training
The selected models were trained on the training dataset. Hyperparameters were tuned using cross-validation to optimize model performance and prevent overfitting.

## Model Evaluation
Models were evaluated using the validation and test datasets. Metrics such as mean absolute error (MAE), mean squared error (MSE), and R-squared were used to assess performance. The best-performing model was selected for processing.

## Model Interpretation
Model results were interpreted to understand the predictions. Feature importance scores, RFE, and SHAP values were used to explain which features had the most significant impact on the model’s decisions. Took the average of all the feature importance and selected the best features.

## Model Deployment
The best-performing model was deployed as a web application using the Streamlit library. The app was hosted on AWS using an EC2 instance, allowing users to input property features and get price predictions in real time. The app also displayed analysis and graphs for user insights.

Deployed Website Link: [http://13.60.162.234:8501/](http://13.60.162.234:8501/)

## Model Monitoring and Maintenance
The model’s performance is continuously monitored to remain accurate over time. Periodic updates and retraining are planned to incorporate new data and features in the project.

## Documentation and Presentation
All steps of the project were thoroughly documented, including methodologies, experiments, and findings. An Excel sheet has been uploaded in the GitHub link which explains the step-by-step flow of the project. A user can take the help of this file to recreate the project.
File name: `Real Estate Price Prediction Project Flow.xlsx`

## Project Review and Reflection
The project was reviewed to identify successes and areas for improvement. A continuous thought process is done to improve this project further. For example: bringing in more data from other cities, incorporating more features and options for the user to select, and incorporating an insights page which would provide more information on the price variation and prediction.



## Installation

1. Clone this repo in your local system.
2. **Create a virtual environment** and install the requirements of this project using the below command:

```sh
pip install -r requirements.txt
```

3. Run the streamlit app.

```sh
streamlit run Home.py
```


## Acknowledgements
[99acres](https://www.99acres.com), CampusX Team

