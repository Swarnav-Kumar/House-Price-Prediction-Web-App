<h1 align="center">House Price Prediction Web App</h1>
<h2 align="center">Python Developer (AI/ML) Assignment - VE3</h2>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a> </li>
    <li><a href="#built-with">Built With</a></li>
      <li><a href="#features-used">Features Used</a> </li>
     <li><a href="#technologies-used">Technologies Used</a> </li>
      <li><a href="#getting-started">Getting Started</a></li>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#usage">Usage</a>
      <ul>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project
This project focuses on developing a comprehensive predictive model to estimate housing prices in Bangalore. The goal is to build a robust machine learning model that can accurately predict house prices based on various factors such as location, size, amenities, and other relevant features. The model will be integrated into a user-friendly web application, enabling users to input details and receive price predictions instantly.

## The project involves several key phases :-

## 1. Data Collection and Preprocessing :- 
The first step is to gather and preprocess a rich dataset containing various features influencing house prices in Bangalore. This includes data cleaning, handling missing values, and feature engineering to create new variables that may improve model performance.

## 2. Exploratory Data Analysis (EDA) :- 
A thorough EDA will be conducted to understand the underlying patterns, correlations, and distributions within the data. This analysis will guide feature selection and provide insights into the most influential factors affecting house prices.

## 3. Model Development :- 
Various machine learning algorithms, such as Linear Regression, Decision Trees, Random Forests, and Gradient Boosting Machines, will be explored and implemented. Hyperparameter tuning, cross-validation, and regularization techniques will be employed to optimize the model’s performance.

## 4. Model Evaluation :- 
The models will be evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to ensure accuracy and reliability. The best-performing model will be selected for deployment.

## 5. Web Application Development :- 
The final model will be deployed within a Flask web application. The application will feature an intuitive user interface where users can input various property details and obtain an estimated price. The web app will also include features such as model explanations, confidence intervals, and possibly a visualization of price trends in different Bangalore neighborhoods.

## 6. Documentation and Deployment :- 
The entire codebase, along with detailed documentation and setup instructions, will be hosted on GitHub. This will include steps for replicating the project, explanations of the model’s workings, and guidelines for future improvements.

<img width="941" alt="Home Page" src="https://github.com/user-attachments/assets/da75abc1-5a55-474a-ba91-987648371800">

<img width="946" alt="Home Page -2" src="https://github.com/user-attachments/assets/93957cc4-1b4b-46f7-934a-6efc0a6db206">

<img width="945" alt="Home Page -3" src="https://github.com/user-attachments/assets/5f7767b0-a95f-4b1d-8d1b-d66101a1eeec">

<img width="943" alt="Home Page-4" src="https://github.com/user-attachments/assets/e1547812-38ed-4bd5-909c-5b23e4ef83e9">

<img width="949" alt="About Us Page" src="https://github.com/user-attachments/assets/905436ce-240f-483c-8b8e-efac5c5b2138">

<img width="946" alt="Working Page" src="https://github.com/user-attachments/assets/c7c7f2dd-5a2f-40b9-9c9f-1f38ee6a5569">

<img width="945" alt="Contact Us Page" src="https://github.com/user-attachments/assets/db56e6eb-7778-4196-8deb-18ff58ba601f">

## Built With

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) <br>
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) <br>

## Features Used

- Predict housing prices in Bangalore based on various features.
- User-friendly web interface to input data and receive predictions.
- Comprehensive data analysis and visualization.
- Backend implemented using Flask web framework.

## Technologies Used

- **Python**: Core programming language for model development and backend.
- **Flask**: Web framework for developing the backend of the application.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **Scikit-Learn**: Machine learning library for model development.
- **Matplotlib/Seaborn**: Data visualization.

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is a list of things that you need to use the software and how to install them.<br>
Before you begin, ensure you have met the following requirements. You can install them by running the provided pip commands.

* Pandas
  ```sh
  pip install pandas
  ```
* Numpy
  ```sh
  pip install numpy
  ```
* Matplotlib
  ```sh
  pip install matplotlib
  ```
* Seaborn
  ```sh
  pip install seaborn
  ```
* Flask
  ```sh
  pip install flask
  ```
## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/predicting-housing-prices.git
    ```
2. Navigate to the project directory:
    ```bash
    cd predicting-housing-prices
    ```
3. Create a virtual environment:
    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:

    - For Windows:
        ```bash
        venv\Scripts\activate
        ```
    - For macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
5. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure the virtual environment is activated.
2. Run the Flask application:
    ```bash
    python app.py
    ```
3. Open your web browser and navigate to `http://127.0.0.1:5000/` to access the web application.
