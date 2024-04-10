# Settyl-Project

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

# Repository Structure:

Project_Code.ipynb:
This Jupyter Notebook file contains the code for the entire project, including data preprocessing, model development, API implementation, and testing. It is created using Google Colab.

README.md:
The README file provides an overview of the project, including its purpose, structure, and usage instructions. It also includes links to relevant resources and external tools used in the project.

data set.zip:
This zip file contains the dataset used for model training and testing. It includes JSON files with external status descriptions and internal status labels.

trained_model.h5:
The trained_model.h5 file contains the saved model weights and architecture after training. It can be loaded to make predictions without retraining the model.

docs:
Documentation for the project, including data preprocessing steps, model architecture, training procedure, API implementation, and testing results.

# How to Use
1. Clone the repository: `(https://github.com/Kadar5692/Settyl-Project.git)`
2. Navigate to the project directory: `Settyl-Project`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the API: `python src/api.py`
5. Access the API at `http://localhost:8000` or by generating public URL in real time and make predictions using external status descriptions.

- **Run the API**: Start the FastAPI application using the provided script. It sets up the API, defines the prediction endpoint, establishes an ngrok tunnel for public access, and runs the server.

- **Access the API**: After running the API, obtain the public URL from ngrok. Use this URL to send POST requests to the `/predict/` endpoint for predictions. Utilize tools like Postman or curl to interact with the API and test its functionality.

# Contributors

- [Kadar Alli Sha](https://github.com/Kadar5692)
