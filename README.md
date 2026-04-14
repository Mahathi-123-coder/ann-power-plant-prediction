#  ANN Power Plant Energy Prediction

 Built an Artificial Neural Network (ANN)-based regression model to predict power plant energy output using temperature, humidity, and pressure.

---

##  Project Overview

This project focuses on predicting the electrical energy output of a power plant using a deep learning approach.
An Artificial Neural Network (ANN) is trained on real-world data to model the relationship between environmental conditions and energy generation.

---

##  Dataset Information

The dataset contains the following features:

* **Temperature (T)**
* **Ambient Pressure (AP)**
* **Relative Humidity (RH)**
* **Exhaust Vacuum (V)**

 **Target Variable:**

* Electrical Energy Output (EP)

---

##  Workflow

1. Data preprocessing
2. Splitting dataset into training and testing sets
3. Feature scaling using StandardScaler
4. Building ANN model using PyTorch
5. Training the model
6. Evaluating performance using MSE and R² score

---

##  Model Architecture

* Input Layer
* Hidden Layer 1: 6 neurons (ReLU)
* Hidden Layer 2: 6 neurons (ReLU)
* Output Layer: 1 neuron (Regression output)

---

##  Model Performance

* **Mean Squared Error (MSE) for test data :** 19.5
* **R² Score:** 0.9316

 The model explains approximately **93% of the variance** in the data.

---

##  Tech Stack

* Python
* PyTorch
* NumPy
* Pandas
* Scikit-learn

---

##  Project Structure

```
ann-power-plant-prediction/
│
├── ann_power_plant_prediction.ipynb
├── powerplant_data.csv
├── README.md
```

---

##  Future Improvements

* Hyperparameter tuning
* Comparing ANN with other ML models
* Deploying the model using a web app

---

##  Author

Mahathi

---
