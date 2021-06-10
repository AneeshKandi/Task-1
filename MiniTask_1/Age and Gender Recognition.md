# Age and Gender Recognition

Have you ever tried guessing people's age by their photos or videos? This project does exactly that. We try to identify the age and gender of a person, from a real-time video stream, as accurately as possible. We are going to use OpenCV and Deep Learning models. Age and Gender detection is a two-step process:

Step 1: Detect faces in the input video stream

Step 2: Extract the face Region of Interest (ROI), and apply the age and gender detector algorithm to predict the age and gender of the person.

The predicted gender will be ‘Male’ or ‘Female’, and the predicted age can be given in the form of a range. 

## Face Detection
For face detection we use **OpenCV with Haar Cascades**. This is a Machine Learning based approach where a cascade function is trained with set of input data. **OpenCV** is short for Open Source Computer Vision. Intuitively by the name, it is an _open-source Computer Vision_ and Machine Learning library. This library is capable of processing real-time image and video while also boasting analytical capabilities. It supports the Deep Learning frameworks TensorFlow, Caffe, and PyTorch. OpenCV contains many pre-trained classifiers for face, eyes, smiles, etc..

## Gender Recognition

For Gender and Face detection, we will be using the **CNN** models trained by two Israel researchers - _Tal Hassner and Gil Levi_ - in 2015. _Convolutional Neural Networks_ (CNNs) are one of the most popular neural network architectures. They are extremely successful at image processing, but also for many other tasks (such as speech recognition, natural language processing, and more). 

## Age Recognition

This part is almost similar to gender recognition. The CNN’s output layer (probability layer) consists of 8 values for 8 age classes (“0–2”, “4–6”, “8–13”, “15–20”, “25–32”, “38–43”, “48–53” and “60-100”). 

The image will be processed first, then the face is detected and after a lot of calculations and algorithms performed on the face, the gender and age is detected and is shown.
