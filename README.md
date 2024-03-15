# Bangalore House Price Prediction Web App

This repository contains code and documentation for a web application that predicts house prices in Bangalore using machine learning. The application provides a user-friendly interface for users to input house features such as location, number of bedrooms, bathrooms, etc., and utilizes a machine learning model to predict the house price.

## Overview

The project aims to assist individuals in Bangalore in estimating the prices of houses based on various features. It utilizes a machine learning model trained on a large dataset of Bangalore houses to make accurate predictions.

## Features

- Predict house prices based on location, number of bedrooms, bathrooms, area, etc.
- User-friendly web interface for easy input and visualization of results.
- Backend powered by Flask for handling requests and serving predictions.
- Extensive data cleaning and preprocessing to ensure model accuracy.
- Comparison of multiple machine learning models to select the best performing one.
- HTML, CSS, and JavaScript used for building the frontend UI.

## Dataset

The dataset used for training the machine learning model consists of a large collection of house listings in Bangalore. It includes various features such as location, size, amenities, and price. The dataset was cleaned and preprocessed to handle missing values, outliers, and categorical variables.

## Machine Learning Model

Multiple machine learning models were trained and evaluated to predict house prices. The best performing model was selected based on evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score. The final model was deployed using Flask to serve predictions in real-time.

## Deployment

The machine learning model is deployed as a web application using Flask. The frontend is built using HTML, CSS, and JavaScript to provide an intuitive user interface. The backend handles incoming requests, processes inputs, and returns predictions to the user.

## Usage

To use the web application:
1. Clone the repository: `git clone https://github.com/RajaBhavesh/House_Prediction_Banglore_Using_ML`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Flask application: `python app.py`
4. Access the web interface in your browser: `http://localhost:5000`

## Future Improvements

- Incorporate additional features such as proximity to schools, hospitals, etc., for more accurate predictions.
- Enhance the UI/UX of the web application to improve user experience.
- Implement user authentication and data persistence for personalized user experiences.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
