IIIT B Assignment using CNN
# Melanoma Detection Assignment
> Melanoma is a type of skin cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. Repository contains a deep learning cnn model that can predict if skin cancer is Melanoma.

## Objective
To build a CNN based model which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The solution analyses a repository which contains various images belonging to following diseases and analyses a dataset. 

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
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)


## General Information
- The solution learns from the dataset provided containing images from the 9 classes. 
- The notebook provides details on how the dataset was used to perform deep learning using cnn model that can be used to  identify Melonnama. 

## Conclusions
- With the first model, we got an overfitted model with training accuracy 82.58% while validation accuracy at 46.75% only.

- For the Second model, we tried data augmentation and using ImageDataGenerator we observed some dicrease in overall accuracy for both train and validation dataset. Training Accuracy=55.41% and Validation Accuracy=53.24%

- We treated class imbalances in the training dataset and with that we were able to get rid of both Overfitting and Underfitting of the model and the overall efficiencies of the model surged to 96.86% for training and 83.89% for validation.

## Technologies Used
- Python 3.2.1, Tensor flow, Keras deep learning cnn module and google col-lab for deep learnig on GPU
 
