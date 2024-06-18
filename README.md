# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Data Reading/Data Understanding → Defining the path for train and test images Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180. Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1). Choose an appropriate optimiser and loss function for model training Train the model for ~20 epochs Write your findings after the model fit. You must check if there is any evidence of model overfit or underfit. Chose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented data : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1). Choose an appropriate optimiser and loss function for model training Train the model for ~20 epochs Write your findings after the model fit, see if the earlier issue is resolved or not? Class distribution: Examine the current class distribution in the training dataset

Which class has the least number of samples?
Which classes dominate the data in terms of the proportionate number of samples? Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1). Choose an appropriate optimiser and loss function for model training Train the model for ~30 epochs Write your findings after the model fit, see if the issues are resolved or not?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the model 1 The accuracy of the model for the Training data set is 82.48%.

The validation loss as observed is very high. For training the loss is less than 0.3265 where are for validation the loss is not more.

This shows that the model is overfitting.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Tensorflow-Keras
- Matplotlib
- glob

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Upgrad CNN

## Contact
Created by [@https://github.com/gbhar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->