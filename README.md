# Melanoma-Detection-

# Problem statement: 
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

# About DataSet:
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

This dataset is slightly imbalanced

By using Augmentor i have added 500 extra images to each class

# Architecture: 

1) Reschaling Layer
2) 64 Conv2D Neurons with Leaky Relu as Activation
3) Batch Normalization Layer
4) 64 Conv2D Neurons with Leaky Relu as Activation followed by Maxpooling
5) 128 Conv2D Neurons with Leaky Relu as Activation 
6) Batch Normalization Layer
7) Dense Layer 512 Neurons with Leaky Relu as Activation
8) Dense Layer with 9 neurons with Softmax Activation for Classification

# Result:

Over all accuracy achieved 60% in Validation dataset
