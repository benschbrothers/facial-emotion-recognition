# Facial Emotion Recognition
## requirements
Python version: 3.7

The following python packages are required
* numpy
* openCV
* pandas
* matplotlib
* tensorflow/keras

## Script finalNet.py
Requirements:
To run this script, the fer2013 data set must be downloaded (e.g., https://www.kaggle.com/deadskull7/fer2013) and placed in the 'src' folder.
By default, this script loads the 'finalNet.h5' model and predicts images from the fer2013.csv data set.

## Script: predictImage.py
The file 'haarcascade_frontalface_default.xml' inside the 'src' folder is required to execute this script. This script can be executed to predict an image (e.g. testImage.png) by passing the image as an argument:
```python
python predictImage.py testImage.png
```
