# MELANOMA DETECTION

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

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
- Importing data set
- Imporing libraries used
- Loading using keras.preprocessing
- Visualize the dataset
- Create the model
- Compile the model
- Train the model


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Data set has been used is from International Skin Imaging Collaboration (ISIC)
- All the images used has been uploaded to git in the folder Skin cancer ISIC The International Skin Imaging Collaboration.
- Here I have not used google colab, so that portion of the code is commented.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Class rebalance reduces overfitting to a large extent.
- Both training and validation accuracy increases when compared to previous models
- Training accuracy is around 94% and validation accuracy is around 77%
- After implementing Augmentor Library, the difference between training and validation accuracy reduced

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
import pathlib
import tensorflow as tf
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
import os
import PIL
from tensorflow import keras
from tensorflow.keras import layers
from tensorflow.keras.models import Sequential

from glob import glob

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@vishnucvinod] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project --># melanoma_assignment