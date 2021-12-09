# Detecting Pneumonia from Chest X-rays using Deep Learning Concepts
This project is about detecting Penumonia from Chest X-rays which are classified as normal and pneumonia classes. 
There are pre-processing techniques used on data.
Processed training images are used to train the model to classify the images.
Processed testing images are used to test the accuracy of the model.

# Dataset:
Dataset can be downloaded from https://www.kaggle.com/tolgadincer/labeled-chest-xray-images

# Running the model:
The data from the URL can be downloaded and should be saved in a folder named 'data' and also the code for the program is saved in same folder(data and code under same folder).
The pre-processing program helps to retrieve the processed images and store the same under data folder with name as 'processed_data' folder.
The processed_data folder contains Training and Testing folders which has images on both classes 'normal' and 'pneumonia'

# Model Details:
I experimented with different data pre-processing techniques and different data augmentation techniques.
I experimented with different CNN models like Nasnet, Inception and VGG out of which Nasnet gave the best performance.
Included the files of pre-processing data and then the main model.
1. pre-processing file is used to process the data and store them in processed_data folder
1. final-Nasnet file has the model which takes processed data and train and test the model.
