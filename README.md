# Image Classification: Birds Species

This project is an image classification model designed to identify birds species using deep learning techniques. The model is built using TensorFlow and Keras, and it is deployed on a Streamlit web application, where users can input image URLs for prediction.

![Project Banner](Images/HomePage.png)

## Project Structure

- **Data**: The model is trained using a dataset containing images of various bird species.
- **Dataset**: `https://www.kaggle.com/datasets/gpiosenka/100-bird-species`
- **Model**: The model is a Convolutional Neural Network (CNN) optimized to classify images of Bird species with high accuracy.

## Features

- **Deep Learning**: Utilizes TensorFlow and Keras for building and training the CNN model.
- **Streamlit Integration**: The model is deployed on a Streamlit app, making it accessible via a web interface.
- **URL-based Predictions**: Users can paste any image URL to get predictions on whether the image is of a Bird Species.

## Usage

1. **Open the Web App**: Launch the Streamlit app using the command above or use my app `https://birds-image-classification-model-3gtmbjda9chcmmhphcb3nk.streamlit.app/`.
2. **Input Image URL**: Copy and paste an image URL into the input box. The image should be a direct link to a bird image.
3. **Predict**: Click "Enter" button to see the model's prediction.

## Model Details

- **Architecture**: The model is a CNN with multiple layers including convolutional layers, pooling layers, and dense layers.
- **Input Dimensions**: The images are resized to 180x180 pixels before being fed into the model.
- **Training**: The model is trained on a well-organized dataset with separate directories for training, validation, and testing.

## Example

- **URL**: Use this example image URL: `https://github.com/KushxKalsi/Birds-Image-Classification-Model/blob/main/Images/Crow.jpg?raw=true`
- **Prediction**: The model will predict "Bird_Species".
