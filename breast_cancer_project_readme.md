# Breast Cancer Prediction Project

## Project Overview
This project uses the **Breast Cancer dataset** to build a predictive model that determines whether a cell is malignant or benign based on specific measurements of its nucleus. The model is implemented using **Python** and trained using **logistic regression**.

The primary goal of this project is to demonstrate how a simple predictive model can be integrated into real-world applications, such as a Flask-based web application, to assist medical professionals in making faster and more informed decisions.

# Access to Full Project
https://colab.research.google.com/drive/1QSg-6pUKk335mKjcoFDucYvDdLQKAeDR?authuser=1#scrollTo=cTdaWh3C32Gb

## Features
- Predicts if a cell is malignant or benign.
- Built with Python and scikit-learn.
- Model can be deployed as an API using Flask.
- Easily extendable to connect with diagnostic machines for automated tissue analysis.

## Dataset
The project uses the publicly available **Breast Cancer dataset**, which contains measurements of various features of cell nuclei.

## How It Works
1. Load and preprocess the dataset.
2. Train a logistic regression model on the training data.
3. Evaluate the model's performance.
4. Use the trained model to make predictions on new samples.

## Usage
1. Install dependencies:
```bash
pip install pandas scikit-learn flask
```

2. Run the notebook or Python scripts to train and test the model.

3. (Optional) Deploy the model with Flask to serve predictions through a web interface.

## Potential Applications
- Doctors can input measurements to receive instant predictions.
- Integration with tissue analysis machines for automated diagnosis.
- Serve as a backend API for healthcare applications.

## License
This project is for educational purposes and does not provide medical advice.

