🚀 Electric Motor Temperature Prediction - Machine Learning Project

📌 Overview

This project is a NCTU Assignment uses Deep Learning (DL) models to predict electric motor temperature based on sensor data. The dataset includes various factors affecting motor temperature, such as ambient temperature and rotational speed.

📊 Dataset

Source: [https://www.kaggle.com/datasets/wkirgsn/electric-motor-temperature]

Features: ['u_q', 'coolant','u_d', 'stator_tooth','motor_speed', 'i_d', 'i_q', 'pm', 'stator_yoke', 'ambient', 'torque']

Target: ['stator_winding']


We trained multiple ML models to predict motor temperature:

Simple MLP

Deep MLP

1D CNN

Autoendcoder + MLP


a GUI for easier monitoring:
![Screenshot 2025-04-30 071003](https://github.com/user-attachments/assets/227eaa97-c8b7-4239-8dbc-03f8996aab96)
![Screenshot 2025-04-30 071022](https://github.com/user-attachments/assets/fe69476f-cd58-45a4-b47b-a5c3eec2f023)
![Screenshot 2025-04-30 071044](https://github.com/user-attachments/assets/1469a6fd-ddaf-4812-8370-74c464c9a0bd)


🛠 Installation & Usage

🔧 Setup

Clone this repository:

git clone https://github.com/AmrKhamis1/DeepLearning_MotorTemp_Prediction.git
cd DeepLearning_MotorTemp_Prediction

Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:

jupyter notebook



