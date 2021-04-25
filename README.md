# Face-Mask-Detection-using-CNN
During pandemic COVID-19, WHO has made wearing masks compulsory to protect against this deadly virus. In this tutorial we will develop a machine learning project – Real-time Face Mask Detector with Python.
Real-Time Face Mask Detector with Python
We will build a real-time system to detect whether the person on the webcam is wearing a mask or not. We will train the face mask detector model using Keras and OpenCV.

## Download the Dataset
The dataset we are working on consists of 1376 images with 690 images containing images of people wearing masks and 686 images with people without masks.

## Download the dataset: Face Mask Dataset

## Download the Project Code
Before proceeding ahead, please download the project source code: Face Mask Detector Project

## Install Jupyter Notebook
In this machine learning project for beginners, we will use Jupyter Notebook for the development. Let’s see steps for the installation and configuration of Jupyter Notebook.

Using pip python package manager you can install Jupyter notebook:

pip3 install notebook
And that’s it, you have installed jupyter notebook

After installing Jupyter notebook you can run the notebook server. To run the notebook, open terminal and type:

jupyter notebook
It will start the notebook server at http://localhost:8888

jupyter notebook

To create a new project click on the “new” tab on the right panel, it will generate a new .ipynb file.

Create a new file and write the code which you have downloaded

## Let’s dive into the code for face mask detector project:
We are going to build this project in two parts. In the first part, we will write a python script using Keras to train face mask detector model. In the second part, we test the results in a real-time webcam using OpenCV.

Make a python file train.py to write the code for training the neural network on our dataset. 
