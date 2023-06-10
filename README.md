# HandHandwritten Devanagari Numeral Recognition

This project focuses on building a system for recognizing handwritten Devanagari numerals. Devanagari numerals are the numerical symbols used in the Devanagari script, primarily in languages such as Hindi, Nepali, and Marathi.The system will take an input image containing a handwritten Devanagari numeral and classify it into one of the ten classes representing the Devanagari numerals from 0 to 9.

# Dataset Description

The dataset used for this project consists of handwritten digit images, each with a resolution of 28x28 pixels. The dataset contains 17,000 images for training and 3,000 images for testing, which were obtained from a folder on the researcher's desktop. The images are in grayscale and have been preprocessed to have pixel values between 0 and 1. The goal of this project is to develop a fully connected neural network that can accurately classify the digits in the images. 

# Architecture 

Convolutional Neural Networks (CNNs) are commonly used for image classification tasks. Start with a simple CNN architecture and adjust its complexity as needed.CNNs consist of multiple layers, including convolutional layers, pooling layers, and fully connected layers.The Proportion of Validation loss is 47.8 % and training loss is 52.2 %The performance of CNNs in handwritten numeral recognition is evaluated using various metrics, including accuracy, precision, recall, and F1-score.According to the data that we were taken, the model classified 98.23% accuracy of the test photos correctly. 

<img width="500" alt="image" src="https://github.com/Asritha10/HDNR/assets/95580777/d5f6c54e-27f5-4cb9-a224-ca3d8f5a83e9">








