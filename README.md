# ⚡ ANN Regression – Power Plant Dataset

## 📌 Project Overview

This project implements an **Artificial Neural Network (ANN) regression model** using the **Combined Cycle Power Plant dataset** to predict electrical energy output.

The project follows a complete deep learning workflow, including data splitting, feature scaling, model definition, training, validation, visualization, loading the best-performing model, and final evaluation using the **R² score**.

## 📊 Dataset

The dataset contains measurements collected from a Combined Cycle Power Plant.

### Input Features

* Ambient Temperature (AT)
* Exhaust Vacuum (V)
* Ambient Pressure (AP)
* Relative Humidity (RH)

### Target

* Electrical Energy Output (PE)

## 🔄 Workflow

1. Load the dataset
2. Split the data into training and testing sets
3. Scale the input features
4. Define the ANN regression model
5. Train the model
6. Validate the model during training
7. Visualize training and validation performance
8. Save and load the best model
9. Evaluate the model on the test dataset
10. Calculate the **R² score**

## 🧠 Model

The ANN consists of an input layer, hidden layers, and an output layer designed for regression.

The model learns the relationship between environmental conditions and the electrical energy produced by the power plant.

## 📈 Evaluation

The model is evaluated using the **R² (R-squared) score**.

Training and validation curves are also visualized to monitor the model's performance during training.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow / Keras
* Jupyter Notebook

## 📁 Project Structure

```text
ANN-Power-Plant-Regression/
│
├── ANN_Power_Plant_Regression.ipynb
├── Power_Plant_Data.csv
├── README.md
└── requirements.txt
```

## 🚀 How to Run

Clone the repository:

```bash
git clone <your-repository-url>
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook cells sequentially to train and evaluate the ANN regression model.

## 🎯 Objective
