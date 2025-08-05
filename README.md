 PlantDisease_Prediction - AI-Based Leaf Disease Detection

PlantDisease_Prediction is an intelligent desktop/web app that uses deep learning (CNN) to detect plant leaf diseases from uploaded images. This project helps farmers, researchers, and students identify plant diseases early using a simple Streamlit interface.

Project Overview

This project is built using:

- **Convolutional Neural Networks (CNN)** for image classification
- **Custom-trained dataset** of diseased and healthy plant leaves
- **Flask + Streamlit (Python)** for the interface and backend model serving


 Features

-  Upload plant leaf images for disease prediction
-  Detect multiple types of plant diseases
-  Shows prediction label with model confidence score
-  Integrated CNN model trained on real dataset
-  Simple and fast user interface using Streamlit



 Project Flow

1. **User uploads** a leaf image via the Streamlit app.
2. **Backend** loads and feeds the image into the trained CNN model.
3. **Model** predicts the disease class and returns the result.
4. **Streamlit app** displays prediction and confidence score.


Tech Stack

| Component   | Technology             |
|-------------|------------------------|
| Interface   | Streamlit              |
| Backend     | Python (Flask)         |
| ML Model    | CNN (TensorFlow/Keras) |
| Dataset     | PlantVillage Dataset   |



## 📂 File Structure

