# Melanoma Detection Assignment
> In this assignment, I have created a  multiclass classification model using a custom convolutional neural network in TensorFlow.
> A CNN based model which can accurately detect melanoma.




<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. In this assignment, I am creating a  multiclass classification model using a custom convolutional neural network in TensorFlow. The model can classify images for malignant and benign oncological diseases (Actinic keratosis,Basal cell carcinoma,Dermatofibroma,Melanoma,Nevus,Pigmented benign keratosis,Seborrheic keratosis,Squamous cell carcinoma,Vascular lesion) 
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Using image augmentation helped prevent the model from memorizing the training data too much (overfitting).
Fixing the imbalance in class distribution helped the model better learn from all types of examples (reducing underfitting).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tensorflow - version 2.8.0
- Numpy - version 1.19.5
- Pandas - version 1.1.5
- Matplotlib - version 3.2.2
- Scikit-learn - version 1.0.2
- Augmentor - version 0.2.10
- PIL - version 7.1.2





