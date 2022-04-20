# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

  * Actinic keratosis
  * Basal cell carcinoma
  * Dermatofibroma
  * Melanoma
  * Nevus
  * Pigmented benign keratosis
  * Seborrheic keratosis
  * Squamous cell carcinoma
  * Vascular lesion

## Conclusions
- When the CNN model trained without any Augmentation strategy or Data Augmentation, the model tends to Overfit.
- When it trained with appropriate augmentation strategy, this slightly reduced the overfit.
- Finally, A CNN model with Batch normalization and Dropout layer trained on Augmented data, it produced much improved model and problem of overfitting also resolved.


## Technologies Used
- tensorflow
- tensorflow.keras
- matplotlib.pyplot
- Seaborn
- numpy
- pandas

## Contact
Created by @baranitharan16 - feel free to contact me!

