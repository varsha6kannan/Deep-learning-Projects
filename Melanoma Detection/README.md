# Project Name- CNN MELANOMA DETECTION ASSIGNMENT
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- There is a image dataset provided for training and it has about 2357 images of malignant and benign oncological diseases.
- These images were formed from the International Skin Imaging Collaboration (ISIC), and all the images are sorted according to the types of skin cancers.
- We are trying to train a neural network model to observe an image of the skin and help us to detect which of the 9 classes of melanomas does it belong to.

- The data set contains the following diseases:
 1. Actinic keratosis
 2. Basal cell carcinoma
 3. Dermatofibroma
 4. Melanoma
 5. Nevus
 6. Pigmented benign keratosis
 7. Seborrheic keratosis
 8. Squamous cell carcinoma
 9. Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1: While training the data it was observed that even though there are sufficient number of images in the training set, the distribution of these images were irregular. Hence dropouts & data augmentation are necessary steps.
- Conclusion 2: Model 1: without any tuning provided Training accuracy of: 86%    Validation accuracy of: 46% [overfitting]
- Conclusion 3: Model 2: with data augmentaion layer + dropout layer Training accuracy of: 58%    Validation accuracy of: 53% [underfitting]
- Conclusion 4 Model 3: with data augmentaion layer + dropout layer + addition of 500 samples in each class(4500 additional training images to solve class imbalance) Training accuracy: 80%    Validation accuracy of: 77% [no overfitting or underfitting observed]

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - tensorflow 2.17.0
- library - keras 3.4.1
- library - Augmentor 0.2.12

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on [this tutorial](https://learn.upgrad.com/course/5798/segment/54249/322681/977150/4884626).


## Contact
Created by [@varsha6kannan] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->