# Project Name
Melanoma Detection


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
**Problem statement:**    
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
**Dataset**   
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
- Initially there was a class imbalance and certain classes had very few smaple. There was a low accuracy and also possible overfitting condition
- After using Image tranformations, handling class balance with Augmentator, drop outs the accuracy increase and also the overfitting is reduced
- Adding more data, and hyper parameter tuning can improve the model further  


## Technologies Used
- Tensorflow - version 2.12.0


## Contact
Created by [@ram-ch] - feel free to contact me!


