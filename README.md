# Self-Driving-Car
We are here building a minimal version of self driving car. Here, we have a front camera view. This will transfer input to the computer. Then Deep Learning algorithm in computer predicts the steering angle to avoid all sorts of collisions. Predicting steering angle can be thought of as a regression problem. We will feed images to Convolutional Neural Network and the label will be the steering angle in that image. Model will learn the steering angle from the as per the turns in the image and will finally predicts steering angle for unknown images.

![Final_short](https://user-images.githubusercontent.com/40149802/65960162-71037480-e471-11e9-92a5-ed0ca6e07af1.gif)

# Dataset

Refer this: https://github.com/SullyChen/Autopilot-TensorFlow


There are total 45406 images in the dataset along with their steering angles. We will split the dataset into train and test in a ratio of 70:30 sequentially.

# Model Preview
![image](https://user-images.githubusercontent.com/40149802/65964220-16224b00-e47a-11e9-92c8-48a2e07014e9.png)

You can download my final model from here: https://drive.google.com/drive/folders/1aw827ecHqYAHr9kdPTpyC6lfX39J1sgV?usp=sharing

# Objective

Our objective is to predict the correct steering angle from the given test image of the road. Here, our loss is Mean Squared Error(MSE). Our goal is to reduce the MSE error as low as possible.

# Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.

Python 3: https://www.python.org/downloads/

Anaconda: It will install ipython notebook and most of the libraries which are needed like pandas, matplotlib, numpy and scipy: https://www.anaconda.com/download/

* Libraries:

Tensorflow: It is a deep learning library.
pip install tensorflow

OpenCV: It is used for processing images.
pip install opencv-python
