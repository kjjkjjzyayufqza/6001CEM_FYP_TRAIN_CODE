# 6001CEM_FYP_TRAIN_CODE

This is my Python code for **FYP**, which is divided into two main functional sections, **Chatbot** and **Dermatological Image Recognition**.

# Chatbot

Through half a year of self-study, I learned to use pytorch for basic machine learning concepts, and completed the part of Chatbot, mainly using **Feedforward Neural Networks (FNN)** and **NLTK** as libraries. `It can only predict data through trained models and is based on classification models, not generative AI`.

- Functionality
	> Provide predictions based on training data.
- limitation
    > Can only be based on trained data and performs very poorly when using data outside of training.
- Future improvements
    > Learn what generative AI is and study how to use and write the code for it.

# Dermatological Image Recognition

The code is developed using CNN techniques and in conjunction with the ResNet18 model. After data cleaning of the training data, the model training was started and the final accuracy was 60%.

- Functionality
	> Provide a picture of the skin and the program will automatically identify if the skin has a disease and if so, which one it belongs to.

## Training data analysis

- Train loss
<img alt="Train loss" src=".\image\test_loss.png" >

- Valid accuracy
<img alt="Valid accuracy" src=".\image\valid_accuracy.png" >

- Test loss
<img alt="Test loss" src=".\image\test_loss.png" >


# All FYP SOURCE CODE
BACKEND-SERVER : https://github.com/kjjkjjzyayufqza/6001CEM_FYP_CHATBOT_PYTHON

WEB : https://github.com/kjjkjjzyayufqza/6001CEM_FYP_WEB

MOBILE : https://github.com/kjjkjjzyayufqza/6001CEM_FYP_MOBILE

TRAIN-CODE : https://github.com/kjjkjjzyayufqza/6001CEM_FYP_TRAIN_CODE
