# How It Works

This project classifies images of **bird species** using a deep learning model built with **TensorFlow** and **Keras**, and makes predictions through a **Streamlit web app**.

## Steps

1. **User Input**

   * The user provides an image URL of a bird on the web app.

2. **Preprocessing**

   * The image is fetched and resized to **180x180 pixels** to match the model’s input requirements.

3. **Prediction**

   * The preprocessed image is passed through the trained **Convolutional Neural Network (CNN)**.
   * The model analyzes features (shapes, colors, textures) to identify the bird species.

4. **Output**

   * The predicted bird species is displayed on the web app.
   * Users instantly see whether their uploaded image matches one of the trained categories.

## Behind the Scenes

* **Dataset**: The model was trained using the [100 Bird Species dataset](https://www.kaggle.com/datasets/gpiosenka/100-bird-species).
* **Model Architecture**: CNN with convolutional, pooling, and dense layers for high accuracy.
* **Deployment**: The model is integrated with a **Streamlit app** for easy, URL-based predictions.

## Example

* Try this image URL:
  `https://github.com/KushxKalsi/Birds-Image-Classification-Model/blob/main/Images/Crow.jpg?raw=true`

* Visit the app:
  [Birds Image Classification App](https://birds-image-classification-model-3gtmbjda9chcmmhphcb3nk.streamlit.app/)

* See the prediction:
  The app will return the **bird species name** predicted by the model.
