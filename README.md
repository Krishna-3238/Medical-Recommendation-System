# Symptom-Based Health Recommendation System

A Flask-based web application that provides health recommendations based on user-inputted symptoms. The system uses machine learning models to predict potential diseases, offers a brief description, and suggests medications, precautions, workouts, and dietary recommendations to guide users on the path to wellness.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Project Structure](#project-structure)
5. [Installation](#installation)
6. [Usage](#usage)


## Project Overview

The Symptom-Based Health Recommendation System allows users to input symptoms and, using machine learning algorithms, predicts possible diseases and provides associated health recommendations. This app is useful for individuals seeking preliminary health insights and suggestions for maintaining or improving their health.

![Sample Output](https://github.com/Krishna-3238/Medical-Recommendation-System/blob/main/output%201.png)
![Sample Output](https://github.com/Krishna-3238/Medical-Recommendation-System/blob/main/output%202.png)


## Features

- **Symptom Input**: Users can enter symptoms via a simple web interface.
- **Disease Prediction**: Based on the symptoms, the model predicts potential diseases.
- **Health Recommendations**: The app provides a description of the predicted diseases, recommended medications, precautions, workouts, and dietary suggestions.
- **High Model Accuracy**: The final model achieves an accuracy and precision of 1.0, ensuring reliable predictions.

## Technologies Used

- **Backend**: Flask
- **Machine Learning Models**: 
  - Support Vector Machine (SVM)
  - Random Forest
  - K-Nearest Neighbors
  - Multinomial Naive Bayes
  - Gradient Boosting
- **Frontend**: HTML templates
- **Data Handling**: Pandas
- **Model Evaluation**: SVM was selected as the final model for its high accuracy and precision.

## Project Structure

- `datasets/`: Contains CSV files with data on symptoms, diseases, descriptions, medications, precautions, workouts, and diets.
- `models/`: 
  - Jupyter notebook with machine learning model training and evaluation.
  - Pickle files of trained models for quick loading during predictions.
- `templates/`: HTML files for the frontend of the web application.
- `Flask_app.py`: The main Flask application file that runs the web app and handles routes.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Krishna-3238/Medical-Recommendation-System.git
   
2. **Install Dependencies**:

   Install the necessary libraries if not already installed:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the System**:

   Run the Python script to start the Laptop-price-Prediction:

   ```bash
   python app.py
   ```
## Usage
1. Enter symptoms in the web form.
2. Submit the form to view the predicted disease(s) along with:
  - Disease description
  - Suggested medications
  - Precautions
  - Recommended workouts
  - Dietary advice

## Contributors
- **Krishnandan sah**
