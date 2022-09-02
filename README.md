# use the face_recognition API and OpenCV in our project.
  <head>
    <title>Face Recognition Reference</title>
  </head>

  <body>
  1. Prepare the dataset
Create 2 directories, train and test. Pick an image for each of the cast from the internet and download it onto our “train” directory. Make sure that the images you’ve selected show the features of the face well enough for the classifier.

For testing the model, let’s take a picture containing all of the cast and place it onto our “test” directory.

For your comfort, we have added training and testing data with the project code.

2. Train the model
First import the necessary modules.
  
import face_recognition as fr
import cv2

import numpy as np
import os

  
  
  
  </body>

