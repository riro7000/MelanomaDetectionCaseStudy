# Melanoma_Detection_Using_CNN

> Objective: Build a multiclass classification model using a custom convolutional neural network in TensorFlow.
Problem Definition : To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

Dataset: The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

Contents:

Data Reading
Train and Test data split
Dataset visualisation
Model Building
Model training
Visualising the model data
Choosing an appropriate data augmentation strategy to resolve underfitting/overfitting
Model Building & training on the augmented data
Class distribution
Handling class imbalances
Model Building & training on the rectified class imbalance data




## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Augmentor library has increased the accuracy of training data

- Model is still slightly overfitting

- The problem of overfitting can be resolved by adding more layers,neurons or adding dropout layers.

- The Model can be further improved by tuning the hyperparameters.

## Technologies Used
- pathlib
- tensorflow 
- matplotlib
- numpy 
- pandas
- os
- PIL
- keras from tensorflow 
- layers from tensorflow.keras 
- Sequential from tensorflow.keras.models
- Augmentor Librarry


Attachments:
- ipynb
- Readme.md

## Contact
Rishi Rohra


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->