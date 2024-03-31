# WASTE SEGREGATION DEEP LEARNING MODEL - Predicting the class of waste
# **Average Accuracy - 75%**
# Site  Demo video - https://drive.google.com/file/d/19-HI_WcwDz2eVxrpojYX48DD0qljUuEf/view?usp=sharing

# DEPLOYED PART - 

The model has been successfully deployed using Flask, Streamlit and is live using ngrok. 
Initially, we considered hosting the model on render and pythonanywhere, but encountered challenges and opted for a different approach. The journey involved downloading a pickle file using the Pickle library, and later transitioning to an HDF5 file for model storage and retrieval. 
Spyder was explored as a potential option, leading to two days of experimentation with various frameworks. 
Despite reaching the final stages of deployment with PythonAnyWhere, render, and Streamlit community cloud unforeseen python and tensorflow version issues disrupted the process. 
We persistently pursued alternatives, highlighting our commitment to overcoming challenges and delivering a seamless user experience. Finally, the site is hosted on ngrok.

# Site link: changes periodically

Problem : Ngrok free plans have a tunnel session timeout. We'll need to restart ngrok periodically to maintain the tunnel.

# SITE DEMO

# <img width="960" alt="Screenshot 2024-02-11 155804" src="https://github.com/Poorvaahuja/waste_management_system/assets/122693422/bd491659-4f11-42cc-b23d-b80c53119e3f">

# <img width="959" alt="Screenshot 2024-02-11 155848" src="https://github.com/Poorvaahuja/waste_management_system/assets/122693422/01df24e8-dddd-4cc5-bf25-38b2a2f7d700">

# <img width="956" alt="image" src="https://github.com/Poorvaahuja/waste_management_system/assets/122693422/0c5ab77c-965f-4dde-a908-473b2fc7343c">

# ![fruits](https://github.com/UPASNA-AGGARWAL/Hackathon_Devacation/assets/120074587/a1585b0f-36d1-4345-8e9c-bfb644f998e8)
when fruit image is  uploaded to test the model, it is classified as organic waste.

# ![organic](https://github.com/UPASNA-AGGARWAL/Hackathon_Devacation/assets/120074587/dbc55612-9d80-4739-b556-c739ddfc87bb)

# ![roll](https://github.com/UPASNA-AGGARWAL/Hackathon_Devacation/assets/120074587/d9541292-ee7d-4ac4-bf64-eb9659d127cf)
when paper roll image is  uploaded to test the model, it is classified as recyclable waste.

# ![recycle](https://github.com/UPASNA-AGGARWAL/Hackathon_Devacation/assets/120074587/6abc9170-2203-4ff6-bf18-11ae72e47e47)

### MODEL DEMO

# <img width="923" alt="image" src="https://github.com/Poorvaahuja/waste_management_system/assets/122693422/2b38e7f9-0424-4dde-bfc2-199084c43e26">

# <img width="728" alt="Screenshot 2024-02-09 192856" src="https://github.com/Poorvaahuja/waste_management_system/assets/122693422/cc02f339-97b3-4c84-ba88-13079db26030">


## Overview
The repository contains two deep-learning models designed for waste segregation, categorizing waste into organic and recyclable classes. The model leverages the ResNet50 architecture and VGG16 architecture and is implemented using TensorFlow and Keras.  For deployment, we opted for the ResNet50 model due to its promising accuracy levels.

## Tech Stack

- **Deep Learning Framework:** TensorFlow
- **Neural Networks API:** Keras
- **Pre-trained Model:** ResNet50, VGG16
- **Activation Function:** SoftMax
- **Layers and Components:** Input, Lambda, Dense, Flatten
- **Libraries:** NumPy, Matplotlib
- **Miscellaneous:** glob, Sequential

## Model Architecture

The model consists of several layers, including Input, Lambda, Dense, and Flatten, orchestrated to efficiently process and classify waste images. The Softmax activation function is employed for precise classification.

## Training Details

- **Number of Epochs:** 20 (ResNet) and 15 (VGG)
- **Training Images:** 22,564
- **Testing Images:** 2,513

This project was inspired by the need for efficient waste management and is a step towards creating a cleaner, more sustainable environment.

