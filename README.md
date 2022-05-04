# X-Ray-Classification
Moravian University CSCI 296 Final Project

Contributors:
	Jack Wagner, Zach Bingaman
	
# Overview 
- Repository holds jupyter notebook files which explore classifying XRay images with Machine Learning
- Part of Kaggle Machine Learning Competition - [XRay Competition](https://www.kaggle.com/competitions/unifesp-x-ray-body-part-classifier/overview)


# Project Details
This Machine Learning project uses DICOM images as the data, and demonstrates exploration, data processing, Machine Learning Model Selection and our final  results for our model

Our dataset has 22 body part labels, 1738 training images and these images are 256 x 256 pixels.
Our type of problem was a multiclass, multiouput classification machine learning problem

**Possible Body Part Labels:**
``` 
    0: 'Abdomen',
    1:'Ankle',
    2: 'Cervical Spine',
    3: 'Chest',
    4: 'Clavicles',
    5: 'Elbow',
    6: 'Feet',
    7: 'Finger',
    8: 'Forearm',
    9: 'Hand',
    10: 'Hip',
    11: 'Knee',
    12: 'Lower Leg',
    13: 'Lumbar Spine',
    14: 'Others',
    15: 'Pelvis',
    16: 'Shoulder',
    17: 'Sinus',
    18: 'Skull',
    19: 'Thigh',
    20: 'Thoracic Spine',
    21: 'Wrist'
    
 ```
- [Exploring](#Exploration)
- [Preparing](#Preparing)


# Exploration
- Our exploration of the data mainly consisted of looking at the different pixel distributions amongst the data.
- One of the interesting things that we found was that not all of the images had uniform pixel measurements.
- As indicated by the below figure we had a very strange histogram of the pixels values in our image data
- <img width="371" alt="Screen Shot 2022-05-04 at 12 07 45 PM" src="https://user-images.githubusercontent.com/78323388/166723752-755cd28d-bcf3-4f77-bdf3-da2f913fb7f4.png">
- This was quite a strange discovery and when looking deeper at the data, we found that one of the labels was 'Others'

- Looking into this others label we found that 'Others' specified that the image was not of a DICOM image type, therefore the pixel measurements were different


# Preparing


# Models


# Fine-Tuning Model


# Final-Results



