# Object-Detection-Model
Project Overview:

- In this project, I Perform Object detections with a pretrained model with the KerasCV Object Detection API.

Project Steps:

- First we Import Packages, then Perform detections with a pretrained model. 
- Next we load an image.
- After some more steps then we Just like any other keras.Model we can predict bounding boxes using the model.predict() API.

Local Setup:

- from tensorflow import data as tf_data
- import tensorflow_datasets as tfds
- import keras
- import keras_cv
- import numpy as np
- from keras_cv import bounding_box
- import os
from keras_cv import visualization
import tqdm
