# Settyl-Project

Sure, here's a suggested description for your GitHub public repository to showcase your submission:

---

# Machine Learning Model for Predicting Internal Status

This repository contains the code and documentation for a machine learning model developed to predict internal status based on external status descriptions. The project was completed as part of a task for the Settyl Data Science and Machine Learning Engineer role.

# Overview

The goal of this project was to develop a robust machine learning model using TensorFlow to predict internal status labels using external status descriptions. The dataset provided was preprocessed to clean and format the data, and various machine learning algorithms and architectures were experimented with to achieve optimal performance.

# Key Features

- **Data Preprocessing**: The dataset was cleaned and formatted to prepare it for training the machine learning model.
- **Model Development**: A machine learning model was developed using TensorFlow with different architectures and algorithms to predict internal status labels.
- **Model Training and Evaluation**: The developed model was trained and evaluated using appropriate metrics such as accuracy, precision, and recall.
- **API Development**: An API was implemented using FastAPI framework to expose the trained machine learning model. The API accepts external status descriptions as input and returns the predicted internal status labels.
- **Testing and Validation**: The API was thoroughly tested to ensure its functionality and accuracy. Predictions were validated against a validation dataset to measure the model's generalization ability.

# Repository Structure

- **data set.json** : Contains the dataset used for training and validation.
- **trained models.h5**: Contains trained machine learning models.
- ** [https://colab.research.google.com/drive/1GFcn2z3XAN1T8kjG8XqeYRNp-4_JQOwS?usp=sharing] **: Google Colab for data exploration, model development, and evaluation.
- **`src/`**: Source code for the API implementation and other utility functions.
- **`docs/`**: Documentation for the project, including data preprocessing steps, model architecture, training procedure, API implementation, and testing results.

# How to Use

1. Clone the repository: `(https://github.com/Kadar5692/Settyl-Project.git)`
2. Navigate to the project directory: `Settyl-Project`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the API: `python src/api.py`
5. Access the API at `http://localhost:8000` and make predictions using external status descriptions.

# Contributors

- [Kadar Alli Sha](https://github.com/Kadar5692)
