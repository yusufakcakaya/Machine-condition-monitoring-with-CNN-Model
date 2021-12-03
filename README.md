# MIMII Dataset Classification 🔊

![9e786f31dfa848b787062bb896ebf186](https://user-images.githubusercontent.com/46165841/144565561-80bcdecf-3c76-4043-9e6e-52394feb3869.png)
## 

## The Mission

Acme Corporation is a worldwide supplier of technological equipment. The factory is facing significant problems with their manufacturing line, the machines are constantly facing failures due to a lack of maintenance and the production is stopped every time an unexpected failure is presented. As a result, Acme is losing millions of U.S. Dollars and important clients like Wile E. Coyote are experiencing delays in deliveries.

The company has collected audio samples of equipment working on normal and anomalous conditions. Their objective is to develop a machine learning model able to monitor the operations and identify anomalies in the sound pattern.

The implementation of this model can allow Acme to operate the manufacturing equipment at full capacity and detect signs of failure before the damage is so critical that the production line has to be stopped.

Our mission is to build a machine learning model for Acme, so they can continue their manufacturing activities and help the Coyote to catch the roadrunner.

![giphy](https://user-images.githubusercontent.com/46165841/144567559-31b66a05-e5b5-40a7-a438-6096c2ef6802.gif)

Used python libraries like ;

 - import librosa
 - import matplotlib.pyplot as plt
 - import librosa.display
 - import numpy as np
 - import pandas as pd
 - from sklearn.preprocessing import scale
 - import os
 - import seaborn as sns
 - import keras
 - from keras.models import Sequential
 - from keras.layers import Dense, Conv2D , MaxPool2D , Flatten , Dropout 
 - from keras.preprocessing.image import ImageDataGenerator
 - from tensorflow.keras.optimizers import Adam
 - from sklearn.metrics import classification_report,confusion_matrix
 - import tensorflow as tf
 - import cv2
 - from glob import glob 


 
#### Which dataset?

The dataset can be downloaded on the following link:

- [Machine Condition Monitoring](https://zenodo.org/record/3384388#.YFIrNXnvJEY)

## Installation

- Pull requests are welcome.
- or ```https://github.com/yusufakcakaya/MIMII-dataset.git```
- 

## Repo Architecture 

```
MIMII-dataset
│
│   README.md              : explains the project
│   
│__   
│   MIMII.ipynb            : main file
│   
│__ 
│   valve                  : to create a .csv file to save bounds and urls
│  
│__ valve_validation       : csv file of bounds
│

```

## Collaborators

Design and construction phase of the project was made by 2 collaborators.([Margaux Benoit](https://github.com/benoitmargx),[Yusuf Akcakaya](https://github.com/yusufakcakaya))
The code while applying the model comes from ([Analyticsvidhya](https://www.analyticsvidhya.com/blog/2020/10/create-image-classification-model-python-keras/).


## Visuals

Examples of outputs.

![download](https://user-images.githubusercontent.com/46165841/144579306-e7b30da8-c269-4b2a-93e0-add833bc4ba9.png)


## Timeline

- Type of challenge: Learning
- Duration: `1 week`
- Deadline : `Thu 02/12/21 H: 4:30 PM`
- Team challenge: Group project

## Good Luck!
