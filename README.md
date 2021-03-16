# Speaker-Recognition-using-MFCC-Features

## General info
This project has the aim to recognize the speaker using MFCC as the features for our model.
We start from 3 recordings of the speakers, we then proceed to apply a Pre-Processing phase 
where we apply a low-pass filter, a normalization, and a transformation to improve the loudness and richness.
Once we are done with pre-processing we proceed to do Data-Augmentation to expand the training data and improve 
the robustness of our model, we will do that randomly adding white noise, time stretching, and pitch shift to our samples.
We will then use Keras to train a model based on the MFCC features of the samples (https://en.wikipedia.org/wiki/Mel-frequency_cepstrum), using this features allows us to reduce the dimensionality of our data and to achieve higher accuracy.

## Technologies
Project is created with:
* numpy
* scipy
* IPython
* pandas
* librosa
* tensorflow
* sklearn
* matplotlib
* suonddevice
  
## Future Improvements
The code for this project is part of a project for a course about Digital Signal and Image Management, the original
code was meant to distinguish between just 3 speakers, will be nice to extend the code to recognize between 
a given number of `n` speakers.
