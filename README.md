# Project Name : Data segregation using CNN

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
  

## General Information
- Improper waste disposal contributes to environmental degradation, increased landfill waste and inefficient recycling processes. Manual sorting is labour-intensive, error-prone and costly hence AI-powered waste classification system addresses these challenges by streamlining waste segregation, reducing operational costs and improving recycling rates.
- This case study involves implementing a custom Convolutional Neural Network (CNN) using the Keras Sequential that helps in classifying the waste.
- The dataset had seven folders, one containing images of each waste category.
- The images are classified into seven categories, namely: Food Waste, Metal, Paper, Plastic, Other, Cardboard, and Glass.
- Approximately 7,000 raw images are divided among the categories.
  

## Conclusions
- The dataset exhibits significant class imbalance with Plastic having 2295 images, much more than the other classes. Cardboard having only 540 images and Glass having 750.
- This suggests that the model may be biased towards the class with more images.
- Hence Data Augmentation and Class Rebalancing techniques were applied using ImageDataGenerator, this involved randomly rotating, translating, flipping or zooming the images. 
- Labels were extracted from folder names and one-hot encoded for compatibility with multi-class classification.
### Before Augmentation
### After Augmentation


## Technologies Used
- numpy: 2.1.3
- pandas: 2.2.3
- seaborn: 0.13.2
- sklearn: 1.6.1
- tensorflow: 2.19.0
- tensorflow keras: 3.9.2


## Acknowledgements
- I would like to express gratitude to the UpGrad IITB Programme for providing me with the opportunity to implement CNN network as part of our coursework. 
- This case study has enriched our understanding and practical application of data analysis techniques, contributing significantly to our learning experience.


## Contact
Created by [@nehasharma5993]


## License
This project is open source and available without restrictions.
