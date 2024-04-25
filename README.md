# LA-final-project
<img width="407" alt="Знімок екрана 2024-04-25 о 23 47 03" src="https://github.com/lizalaveikina/LA-final-project/assets/116552566/e713e448-4f9a-4e7a-9281-7a876133d101">

**Topic: Brain aneurysm classification through MRI and CT images**\
Authors: **Anastasia Plaskonis, Yelyzaveta Laveikina, Veronika Charnosh**
## Explanation of the general topic
The general topic of this report is the detection of brain aneurysms through MRI imaging using computer vision techniques.
## Detailed description of the problem
Solving the problem involves creating an algorithm capable of identifying brain aneurysms from MRI images with high sensitivity and specificity.\
The challenge is to minimize **false positives** (where the algorithm incorrectly iden- tifies an aneurysm where there is none) and **false negatives** (where the algorithm fails to detect an existing aneurysm). This requires the algorithm to effectively differentiate between normal brain structures and aneurysms, despite the complex and variable nature of MRI images.
## Preprocessing algorithms
### Median filter
**Median filtering** is a common digital image processing technique used to reduce noise while preserving the edges and details of an image. It operates by replacing each pixel’s value with the median value of the intensity levels in a local neighborhood around that pixel.
### Gaussian filter
**A Gaussian filter** is a type of digital image processing filter that is commonly used to reduce noise and smooth out images. It is popular for its simplicity, effectiveness, and ability to preserve image details while reducing noise. It operates by convolving an image with a Gaussian function, which represents a bell-shaped curve that smoothly decreases as it moves away from the central point.
### Sobel edge detection
**Sobel edge detection** is a popular technique in image processing and computer vision used to detect edges in images. The Sobel operator works by calculating **the gradient of the image intensity at each pixel.**
The gradient represents the rate of change of intensity in the image and is used to highlight regions of significant change, which typically correspond to edges.
## Description of the algorithm PCA that applies LA principles
Principal Component Analysis (PCA) is a dimensionality reduction technique widely used in data analysis and machine learning. Its primary goal is to transform high- dimensional data into a lower-dimensional representation, capturing the most important information.
## Classification algorithm
### K-Nearest Neighbors (KNN) 
It is an algorithm used in machine learning for classification tasks. It works by storing all available cases and classifying new cases based on a similarity measure. 
## Evaluation of results
### The Receiver Operating Characteristic (ROC) curve
It is a graphical representation that illustrates the performance of a binary classification model across various threshold settings. It plots the true positive rate (TPR) against the false positive rate (FPR) at various threshold values.





