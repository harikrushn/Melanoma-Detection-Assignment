# Melanoma-Detection-Assignment
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

### This model can be used to detect 9 types of malignant and benign oncological diseases
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Malenoma Detection problem is approached with CNN where four convolutional layers and one dense layers are used 
- Four Convolutional layers consist of 32,32,64 and 128 units respectively with 3x3 kernel 
- Convolutional layers are followed by MaxPooling layer and dropout layer
- Dense layer consists of 128 units 
- All layers except dense layers have `relu` activation function, dense layer has `softmax` activation function


## Conclusions
Final model is having 80% validation accuracy after 30 epochs


## Technologies Used
- library - Numpy 1.22.0
- library - Pandas 1.3.5
- library - Tensorflow 2.0.0


## Contact
Created by [@harikrushn] - feel free to contact me!
