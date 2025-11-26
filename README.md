Heart Disease Risk Prediction App 

Overview

This is a web application built with Streamlit that predicts the risk of Coronary Heart Disease (CHD) in a patient based on specific health metrics. It uses a pre-trained Machine Learning model deployed directly to the cloud.

Features

Interactive Interface: Users can input patient data via a sidebar.

Real-time Prediction: The app processes inputs and provides an immediate risk assessment (Low Risk vs. High Risk) along with a probability score.

Data Visualization: Displays a summary dataframe of the input parameters before prediction.

Input Parameters

The model uses the following clinical features for prediction:

SBP (Systolic Blood Pressure): Range 100-220.

LDL (Low-Density Lipoprotein): Cholesterol levels.

Adiposity: Body fat percentage.

Obesity (BMI): Body Mass Index.

Age: Patient's age.

Family History: Presence or absence of heart disease in the family.

Tech Stack

Python

Streamlit (Frontend & UI)

Scikit-learn / Joblib (Model Inference)

Pandas (Data Manipulation)

How to Run Locally

Clone the repository:

git clone [https://github.com/your-username/miniapp-streamlit.git](https://github.com/your-username/miniapp-streamlit.git)
cd miniapp-streamlit


Install dependencies:

pip install -r requirements.txt


Run the app:

streamlit run app.py


Project Structure

app.py: Main application script containing the UI and logic.

Model.pkl: Pre-trained machine learning model.

requirements.txt: List of Python dependencies required for deployment.
