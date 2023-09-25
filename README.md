# Diabetes Classification

This is the README file for the "Diabetes Classification" project. The project focuses on classifying individuals as diabetic or non-diabetic based on several health-related features. The classification model is implemented as a Flask web application, allowing users to input health data and receive predictions about their diabetic status.

## Project Repository

You can find the project's code and files in the following GitHub repository:

[Diabetes Classification GitHub Repository](https://github.com/2611ansh/diabetes-classification.git)

## Getting Started

To run the project locally, follow these steps:

1. Clone the project repository to your local machine:

   ```bash
   git clone https://github.com/2611ansh/diabetes-classification.git
   ```

2. Navigate to the project directory:

   ```bash
   cd diabetes-classification
   ```

3. Install the required Python packages. It's recommended to use a virtual environment:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:

   ```bash
   python app.py
   ```

   The application will be accessible at [http://localhost:5000](http://localhost:5000) in your web browser.

## Usage

Once the application is running, you can access it through your web browser. The following routes are available:

- `/`: The home page of the application, where you can enter health data for prediction.
- `/predictdata`: The endpoint for predicting diabetic status based on input health data.

## Input Health Data

To make a prediction, enter the following health data on the `/` page:

- Pregnancies
- Glucose level
- Blood Pressure
- Skin Thickness
- Insulin level
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age

## Prediction

After entering the required health data, click the "Predict" button. The application will use the trained model to predict whether the individual is diabetic or non-diabetic, and the result will be displayed on the prediction page.

## Model and Data Preprocessing

The project uses a pre-trained classification model loaded from the `Model/modelForPrediction.pkl` file. Data preprocessing is performed using a Standard Scaler loaded from the `Model/standardScalar.pkl` file.


## Acknowledgments

- The dataset used for training and testing the classification model.
- Flask for creating the web application.
- Scikit-learn for machine learning functionalities.
- The open-source community for valuable resources and inspiration.

Feel free to reach out for any questions or suggestions related to this project. Happy classifying!
