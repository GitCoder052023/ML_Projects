# Internet Usage Prediction App

This is the README file for a Python application that predicts internet usage based on the year using a linear regression model.

## Features:

- Predicts internet usage for any year: Simply enter a year in the text field and click the "Predict Usage" button. The app will use the trained model to estimate the internet usage for that year.
- Easy to use: The interface is simple and intuitive, making it accessible to users without any technical knowledge.
- Built with PyQt5: The app is developed using the PyQt5 library, ensuring a native look and feel on different operating systems.

## Requirements:
- Python 3.6 or later
- PyQt5
- NumPy
- scikit-learn

## Instructions:

- Make sure you have the required libraries installed (instructions can be found online).
Run the main script main.py.
- Enter a year in the text field and click "Predict Usage".
- The predicted internet usage for that year will be displayed.

## Data Source:
The internet usage data used in this application is assumed to be stored in the Dataset.internet module. Please ensure this module exists and contains the necessary data arrays years and usage.

## Model Training:

The linear regression model is trained on the provided data during the initialization of the application. You can modify the training process within the MainWindow class if needed.

## Conclusion:

This application demonstrates a basic example of using machine learning to predict values based on historical data. It leverages Python libraries and Qt for a user-friendly interface. Feel free to explore and customize the code further to fit your specific needs!
