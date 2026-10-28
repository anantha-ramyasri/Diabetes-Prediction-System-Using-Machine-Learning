# Diabetes Prediction System Using Machine Learning

## Project Overview

The Diabetes Prediction System is a machine learning web application developed using Python and Flask. It accepts health-related inputs through a web form and uses a trained machine learning model to predict whether the input indicates a possible risk of diabetes.

The project demonstrates data preprocessing, machine learning classification, model evaluation, and integration of a trained model into a web application.

## Technologies Used

- **Programming Language:** Python
- **Web Framework:** Flask
- **Machine Learning:** Scikit-learn
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib
- **Frontend:** HTML, CSS
- **Development Environment:** Jupyter Notebook

## Features

- User-friendly web interface for entering health-related details
- Data preprocessing and missing-value handling
- Feature standardization before prediction
- Machine learning classification using a trained Random Forest model
- Prediction results displayed through the Flask application
- Model development and evaluation using Jupyter Notebook

## Machine Learning Algorithms

The project notebook compares the following classification algorithms:

- Gaussian Naive Bayes
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

The Flask application uses the saved Random Forest model for predictions.

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/anantha-ramyasri/Diabetes-Prediction-System-Using-Machine-Learning.git
```

### 2. Navigate to the project folder

```bash
cd Diabetes-Prediction-System-Using-Machine-Learning
```

### 3. Install the required libraries

```bash
pip install flask pandas numpy matplotlib scikit-learn
```

### 4. Run the Flask application

Make sure the application file, saved model files, and HTML templates are present in their expected locations.

```bash
flask run
```

### 5. Open the application

Open your browser and visit:

http://127.0.0.1:5000/

Enter the requested health information and submit the form to view the prediction.

## Project Structure

```text
Diabetes-Prediction-System-Using-Machine-Learning/
├── app.py
├── rf_model.pkl
├── scaler.pkl
├── imputer.pkl
├── templates/
│   └── index.html
├── diabetes Model_new_final.ipynb
└── README.md
```

*Update the structure above if your repository uses different filenames or folders.*

## Skills Demonstrated

- Python programming
- Data cleaning and preprocessing
- Pandas and NumPy
- Data visualization using Matplotlib
- Machine learning classification
- Model evaluation
- Flask web application development
- HTML and CSS
- Machine learning model integration

## Future Improvements

- Perform cross-validation and hyperparameter tuning.
- Improve input validation and error handling.
- Enhance the user interface and deploy the application.
- Further evaluate model reliability and limitations.

## Disclaimer

This project is intended for educational purposes only. Its predictions are not medical diagnoses and should not replace professional medical advice.

## Author

**Anantha Ramya Sri**

GitHub: [anantha-ramyasri](https://github.com/anantha-ramyasri)
