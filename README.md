# Hackathon_Devacation
 # WASTE SEGREGATION DEEP LEARNING MODEL - Predicting the class of the waste

# **Average Accuracy - 75%**

# DEPLOYED PART - 

The model has been successfully deployed using Flask and is on the verge of going live on PythonAnywhere. 
Initially, we considered utilizing Streamlit for hosting the model, but encountered challenges and opted for a different approach. The journey involved downloading a pickle file using the Pickle library, and later transitioning to an HDF5 file for model storage and retrieval. Spyder was explored as a potential option, leading to two days of experimentation with various frameworks. Despite reaching the final stages of deployment with Ngrok, unforeseen API issues disrupted the process. We persistently pursued alternatives, highlighting our commitment to overcoming challenges and delivering a seamless user experience.


### MODEL DEMO

<img width="923" alt="image" src="https://github.com/Poorvaahuja/waste_management_system/assets/122693422/2b38e7f9-0424-4dde-bfc2-199084c43e26">

<img width="728" alt="Screenshot 2024-02-09 192856" src="https://github.com/Poorvaahuja/waste_management_system/assets/122693422/cc02f339-97b3-4c84-ba88-13079db26030">


### SITE DEMO

<img width="960" alt="Screenshot 2024-02-11 155804" src="https://github.com/Poorvaahuja/waste_management_system/assets/122693422/bd491659-4f11-42cc-b23d-b80c53119e3f">

<img width="959" alt="Screenshot 2024-02-11 155848" src="https://github.com/Poorvaahuja/waste_management_system/assets/122693422/01df24e8-dddd-4cc5-bf25-38b2a2f7d700">

<img width="956" alt="image" src="https://github.com/Poorvaahuja/waste_management_system/assets/122693422/0c5ab77c-965f-4dde-a908-473b2fc7343c">

## Overview
The repository contains a deep learning model designed for waste segregation, categorizing waste into organic and recyclable classes. The model leverages the ResNet50 architecture and is implemented using TensorFlow and Keras.

## Tech Stack

- **Deep Learning Framework:** TensorFlow
- **Neural Networks API:** Keras
- **Pre-trained Model:** ResNet50
- **Activation Function:** Softmax
- **Layers and Components:** Input, Lambda, Dense, Flatten
- **Libraries:** NumPy, Matplotlib
- **Miscellaneous:** glob, Sequential

## Model Architecture

The model consists of several layers, including Input, Lambda, Dense, and Flatten, orchestrated to efficiently process and classify waste images. The Softmax activation function is employed for precise classification.

## Training Details

- **Number of Epochs:** 20
- **Training Images:** 22,564
- **Testing Images:** 2,513

This project was inspired by the need for efficient waste management and is a step towards creating a cleaner, more sustainable environment.

