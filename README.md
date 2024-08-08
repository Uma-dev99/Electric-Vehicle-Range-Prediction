# Electric Vehicle Range Prediction

## Objective
The project aims to predict the range of electric vehicles (EVs) based on various factors such as battery capacity, driving conditions, environmental variables, and vehicle specifications. Accurate range prediction is essential for enhancing the user experience, optimizing energy consumption, and improving the overall efficiency of electric vehicles.

## Project Overview
Electric vehicle range prediction is a critical task that helps alleviate range anxiety, a common concern among EV owners. This project leverages machine learning techniques to build a predictive model that estimates how far an electric vehicle can travel before needing to recharge.

## Key Steps Involved

1. **Data Collection and Preprocessing**
   - Gathered and cleaned data from relevant sources, including battery performance metrics, driving patterns, and environmental conditions.
   - Preprocessed the data to handle missing values, normalize features, and perform feature engineering.

2. **Exploratory Data Analysis (EDA)**
   - Conducted a thorough EDA to identify key features influencing vehicle range.
   - Visualized relationships between variables to gain insights into factors affecting range.

3. **Model Development**
   - Employed various machine learning algorithms such as Linear Regression, Random Forest, and Gradient Boosting to predict vehicle range.
   - Fine-tuned hyperparameters to optimize model performance.

4. **Model Evaluation**
   - Evaluated models using performance metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²).
   - Compared the performance of different models to select the best one.

5. **Prediction and Inference**
   - Used the trained model to make predictions on new data, providing accurate range estimates under different conditions.


## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, Numpy, Scikit-learn, Matplotlib
- **Tools:** Jupyter Notebook, Poetry for dependency management

## Installation and Setup

To get started with this project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Uma-dev99/electric-vehicle-range-prediction.git
   cd electric-vehicle-range-prediction
   ```
2. **Install Poetry**
   ```
   poetry install
   ```
3. **Activate Virtual Environment**
   ```
   poetry shell
   ```
5. **Run Jupyter Notebook**
   ```
   jupyter notebook electric_vehicle_range_prediction.ipynb
   ```
