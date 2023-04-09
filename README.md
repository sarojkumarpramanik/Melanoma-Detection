# Melanoma-Detection
To build a CNN based model which can accurately detect melanoma.

## Table of Contents
* [General Info](#Abstract)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [References](#references)

## Abstract
There are more than 200 different types of cancer, with melanoma being the most deadly form of skin cancer. The diagnosis process for melanoma begins with a clinical screening, followed by dermoscopic analysis and histopathological examination. Early detection of melanoma skin cancer is crucial, as it is highly treatable if identified at an early stage. The first step in diagnosing melanoma is to visually examine the affected skin area, followed by the capture of dermatoscopic images of skin lesions using high-speed cameras. Dermatoscopic images can provide a diagnosis accuracy of 65-80% for melanoma without any additional technical support. The accuracy of melanoma diagnosis can further improve up to 75-84% with additional visual examination by cancer treatment specialists and analysis of dermatoscopic images. This project aims to develop an automated classification system that utilizes image processing techniques to classify skin cancer based on skin lesion images.

## Problem Statement
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Motivation
The main objective of this project is to assist in reducing the number of deaths caused by skin cancer. The project is primarily driven by the desire to utilize advanced image classification technology for the betterment of people's health. With the advancements in machine learning and deep learning techniques, computer vision has made significant progress, making these technologies scalable across various domains.

## Dataset
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

## Conclusions
- The final model used the Augmentor library to artificially generate enough samples to come up with a model that can detect a correct cancer type.
- The augmentor package added more samples to the sparse classes by using techniques like rotation, scaling, and flipping, to increase the variety of the data.
- The performance of the model was good, with a training accuracy of 91%, indicating that it was able to effectively learn from the data and generalize to new examples. This model was chosen as the final model.

## Technologies Used
- keras==2.12.0
- tensorflow==2.12.0
- Augmentor==0.2.12
- pandas==1.4.4
- numpy==1.22.4
- matplotlib==3.7.1

## References
Melanoma Skin Cancer from https://www.cancer.org/cancer/melanoma-skin-cancer/about/what-is-melanoma.html

Introduction to CNN from https://www.analyticsvidhya.com/blog/2021/05/convolutional-neural-networks-cnn/

Image classification using CNN from https://www.analyticsvidhya.com/blog/2020/02/learn-image-classification-cnn-convolutional-neural-networks-3-datasets/

Efficient way to build CNN architecture from https://towardsdatascience.com/a-guide-to-an-efficient-way-to-build-neural-network-architectures-part-ii-hyper-parameter-42efca01e5d7

## Contact
Created by [@sarojkumarpramanik] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->
