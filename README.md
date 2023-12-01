# video-calssification

In this project, I have build video classification model using EfficientNetB0 and BiLSTM model to classify video dataset.
This code uses videos as inputs and outputs class names and predicted class scores for each 20 frames in the score mode.
The backnbone CNN model used to extract features from each image and given inputed to BiLSTM which is a sequencial model which deduces the sequencial information in videos.

#Requirements
Tensorflow
Python 3
Cuda
Matplotlib
Numpy
Pandas
open-cv
gc
generator

#Usage
Assume dataset in /home folder. Each classes should have its folder and inside videos.
/home
  |
    Swimming
      |
        video1.avi
        ...
    Push Up
     |
       video1.avi
       ...
