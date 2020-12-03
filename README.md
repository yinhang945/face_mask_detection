# Face_Mask_Detection
A capstone project for face mask detection using CNN.



<p align="Left">
<img src="images/header.png" width="1000" height="200">
</p>


# Are you wearing a face mask today? 
## A convolutional neural network solution to determine if a person is wearing a mask or not.

## Introduction 
Masks play a crucial role in protecting the health of individuals against respiratory diseases, as is one of the few precautions available for COVID-19 in the absence of immunization. We are going to construct a CNN model to detect if a person is wearing mask or not. 

## Why we need to wear face masks during COVID-19 pandemic
According to CDC Guidance:
*People age 2 and older should wear masks in public settings and when around people who don’t live in their household.​
*Masks offer some protection to you and are also meant to protect those around you, in case you are unknowingly infected with the virus that causes COVID-19.
*A mask is NOT a substitute for social distancing. Masks should still be worn in addition to staying at least 6 feet apart.

<p align="center">
<img src="images/why_wear_mask.png" width="800" height="1000">
</p>

## Goal
Accurately classify whether the person on a given image is wearing a face mask or not.

## Dataset
The dataset contains 1006 images of human faces wearing or not wearing face masks. It has been divided into the training, validation and testing set with two labels: mask and no mask. Each label contains equal number of images for training, validation and testing set.

<a href="https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color">
<p align="center">
<img src="graphics/pie_chart.png" width="800" height="450">
</a>

## Model Framework
I used a keras Sequential model with 9 layers

<p align="left">
<img src="graphics/model.png" width="200" height="400">
</p>

## Results

* My train set ran with **96% accuracy**
* My validation set ran with **93% accuracy**
* My holdout set ran with **92% accuracy**

<p align="left">
<img src="graphics/training-test-accuracy.png" width="350" height="350">
</p>
<p align="left">
<img src="graphics/training-results.png" width="400" height="100">
</p>
                                                                
### Confusion Matrix

<p align="center">
<img src="graphics/confusion-matrix.png" width="850" height="700">
</p>
