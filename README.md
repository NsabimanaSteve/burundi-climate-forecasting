# burundi-climate-forecasting
Machine learning pipeline for climate and hydrological forecasting in Burundi , precipitation, temperature, Rusizi River and Lake Tanganyika water levels (2025–2030)

PROJECT TITLE: EXPLORING ARTIFICIAL INTELLIGENCE FOR ENHANCING 
CLIMATE CHANGE FORECASTING AND MITIGATION 
STRATEGIES IN BURUNDI

AUTHOR: Eunice Sayubu & Steve Nsabimana
ID: 60192026 & 36422026

---

1. GITHUB REPOSITORY
   The full source code for this project is available at:
https://github.com/NsabimanaSteve/burundi-climate-forecasting.git

---

2. PROJECT OVERVIEW
This project investigates the use of Artificial Intelligence models to improve climate forecasting and disaster risk mitigation in Burundi,
a country highly vulnerable to climate change but lacking localized AI-based systems. Multiple models, including Linear Regression, ARIMA, 
Random Forest, XGBoost, LSTM, CNN, and ensemble methods, were implemented and compared across four climate variables: precipitation, temperature,
and water levels of the Rusizi River and Lake Tanganyika. The results show that no single model consistently outperformed others, with different 
models excelling depending on the variable being predicted. Traditional statistical methods such as ARIMA remained competitive, outperforming AI models
in certain cases like Lake Tanganyika water level prediction. Overall, the study demonstrates the potential of combining AI and traditional approaches to 
build reliable, data-driven climate forecasting systems in data-scarce environments like Burundi.

It includes:

* Data preprocessing and cleaning
* Feature selection and scaling
* Training multiple models (e.g., Linear Regression, Random Forest, XGBoost, LSTM)
* Model evaluation using standard metrics
* Model interpretation using SHAP and LIME
* Future Prediction (2025-2030)

---

3. SYSTEM REQUIREMENTS

To run this project, ensure the following are installed:

* Python 3.8 or higher
* pip (Python package manager)

Required Python libraries include:

numpy
pandas
matplotlib
seaborn
scikit-learn
statsmodels
xgboost
tensorflow
shap
lime

Install all dependencies using:

pip install numpy pandas matplotlib seaborn scikit-learn statsmodels xgboost tensorflow shap lime joblib

---

4. HOW TO RUN THE PROJECT

Step 1: Extract the ZIP file

Step 2: Open the project folder

Step 3: Set up the dataset

* Navigate to the folder
* Locate the dataset file
* Update the dataset file path in the code to match your local system

---

Step 4: Run the project

Using a Jupyter Notebook:

* Open the notebook file (.ipynb)
* Run all cells sequentially

---

5. DATASET INFORMATION
   The dataset used in this project is located in the same directory.

Users must ensure:

* The dataset file exists
* The file path is correctly updated in the code

---

6. MODELS USED

The project explores multiple machine learning and deep learning models, including:

* Linear Regression
* Random Forest 
* XGBoost Regressor
* ARIMA 
* LSTM 
* CNN
*Simple Ensemble, Weighted Ensemble, Stacking Ensemble
---

7. EVALUATION METRICS

Models are evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score
* Nash-Sutcliffe Efficiency(NSE)

---

9. MODEL INTERPRETATION

The project includes model explainability using:

* SHAP (SHapley Additive exPlanations)
* LIME (Local Interpretable Model-Agnostic Explanations)

---
10. LOW FIDELITY PROTOTYPE

https://burundai-climate-vision.lovable.app/predictions

11. IMPORTANT NOTES

* Ensure all dependencies are installed before running the code
* Update dataset file paths before execution
* Some models (e.g., LSTM) may take longer to train
* The project was originally developed in a notebook environment (e.g., Google Colab), so minor adjustments may be needed when running locally

---

12. USER GUIDE (BASIC)

13. Install required libraries

14. Load the dataset

15. Update file paths if needed

16. Run the code (notebook or script)

17. View results (plots, metrics, predictions)

---
