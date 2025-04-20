
Insurance Price Prediction

A Machine Learning based project , to calculate the the price of insurance for any person based on some criteria


## Features

- Have multiple criteria
- Instant result
- Fullscreen mode


## Requirements

install Python

### Python Libraries

1. flask
2. joblib
3. sklearn
4. jsonify (from Flask)

### Command to install theses Libraries

pip install flask joblib scikit-learn

## Project Folder Structure

your_project/

│

├── app.py

├── rfmodel.lb              # Pre-trained mode file

├── templates/

│   ├── home.html

│   ├── input_form.html

│   └── prediction_page.html

## Getting started

1. Start the Flask App
python app.py

It will run the server on:
http://0.0.0.0:2525/  or http://localhost:2525/

## Interacting with the Web App

Navigate to / → Home page

/input_form → Form to enter data

Submit form → /prediction → Predicts using the model and displays result
## 🧠 Notes

1. rfmodel.lb is a scikit-learn Random Forest model saved using joblib. Make sure it exists in the same directory.

2. input_form.html should have a form with input fields: region, children, gender, age, bmi, smoker.
