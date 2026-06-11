# Insurance Cost Prediction Using Machine Learning

This repository contains a Streamlit web application for predicting insurance costs based on user input. The predictive model is developed using Machine Learning techniques and helps estimate insurance charges accurately using demographic and health-related information.

## Business Problem

Develop a predictive model to estimate insurance costs based on customer attributes such as age, BMI, smoking status, diabetic condition, number of children, and region. Accurate predictions help insurance companies improve risk assessment and financial planning.

## Dataset

* The dataset contains demographic and health-related information.
* Features include age, gender, BMI, blood pressure, smoking status, diabetic status, number of children, and region.
* The target variable is the insurance cost/claim amount.

## Tasks

1. **Data Preprocessing**

   * Handle missing values.
   * Encode categorical variables.
   * Scale numerical features where required.

2. **Exploratory Data Analysis (EDA)**

   * Analyze data distributions.
   * Identify trends and relationships.
   * Perform correlation analysis.

3. **Feature Selection**

   * Select important features contributing to insurance cost prediction.

4. **Model Selection**

   * Compare multiple regression algorithms.
   * Choose the best-performing model.

5. **Model Training**

   * Split data into training and testing sets.
   * Train regression models on the dataset.

6. **Model Evaluation**

   * Evaluate performance using MAE, MSE, RMSE, and R² Score.

7. **Hyperparameter Tuning**

   * Optimize model performance through parameter tuning.

8. **Deployment**

   * Deploy the trained model using Streamlit for real-time predictions.

## Business Impact

The model provides accurate insurance cost estimates that help insurance companies improve decision-making, resource allocation, risk management, and financial forecasting.

## Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ManiramSwami/Insurance-Cost-Prediction-ML.git
   cd Insurance-Cost-Prediction-ML
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**

   ```bash
   streamlit run app.py
   ```

4. **Open in Browser**

   Visit:

   ```text
   http://localhost:8501
   ```

## App Interface

The application allows users to enter details such as age, gender, BMI, blood pressure, diabetic status, number of children, smoking status, and region. After clicking the **Predict** button, the model generates an estimated insurance cost.

## Files

* **app.py** – Main Streamlit application.
* **insurance.pkl** – Trained Machine Learning model.
* **requirements.txt** – Project dependencies.
* **README.md** – Project documentation.

## Model Training

The predictive model is trained using Machine Learning regression algorithms on insurance data. The final model is saved using Pickle and integrated into the Streamlit application for real-time predictions.

## Contributing

Contributions, suggestions, and improvements are welcome. Feel free to open an issue or submit a pull request.

## Author

**Maniram Swami**

