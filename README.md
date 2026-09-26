# Sensor Occupancy Classification

A machine learning project for predicting whether an environment is **occupied or unoccupied** using sensor data.

## 📌 About the Project

The project uses sensor readings to classify the occupancy status of an environment.

### Features

* Temperature
* Humidity
* Light
* CO2
* HR

### Classes

* `0` → Unoccupied
* `1` → Occupied

## 🤖 Machine Learning

The model is trained using **ML for Kids** and uses the sensor values as input to predict the occupancy class.

The dataset is divided into **training** and **testing** sets using an 80/20 split.

## 📊 Evaluation

The model is evaluated using:

### Accuracy Score

Accuracy Score measures the percentage of correctly classified samples.

```python
accuracy_score(y_true, y_pred)
```
sensor_project_AccuracyScore=0.9962546816479401
### Confusion Matrix

The Confusion Matrix compares the actual labels with the predicted labels.

```python
confusion_matrix(y_true, y_pred)
```

<img width="514" height="448" alt="image" src="https://github.com/user-attachments/assets/ebf94595-7b7f-4b54-9ae9-12aa93601411" />


## 📁 Project Files

```text
├── sensor.ipynb
├── data_0.csv
├── data_1.csv
├── data_0_train.csv
├── data_0_test.csv
├── data_1_train.csv
├── data_1_test.csv
├── prediction_0.csv
├── prediction_1.csv
├── prediction.xlsx
└── a.txt
```

## 🛠️ Requirements

```text
ydf==0.8.0
pandas==3.0.1
requests==2.32.5
```

Install the dependencies with:

```bash
pip install -r a.txt
```

## ▶️ Usage

Open `sensor.ipynb` in Jupyter Notebook and run the cells to:

1. Load the dataset
2. Prepare the training and testing data
3. Make predictions using the trained model
4. Calculate the Accuracy Score
5. Generate the Confusion Matrix
6. Save the prediction results

## 🎯 Goal

The goal of this project is to use machine learning to automatically detect whether an environment is **occupied or unoccupied** based on sensor measurements.
