# Age and Gender Recognition

Have you ever tried guessing people's age by their photos or videos? This project does exactly that. We try to identify the age and gender of a person, from a real-time video stream, as accurately as possible. We are going to use OpenCV and Deep Learning models. Age and Gender detection is a two-step process:

Step 1: Detect faces in the input video stream

Step 2: Extract the face Region of Interest (ROI), and apply the age and gender detector algorithm to predict the age and gender of the person.

The predicted gender will be ‘Male’ or ‘Female’, and the predicted age can be given in the form of a range. 

## Face Detection
For face detection we use OpenCV with Haar Cascades. This is a Machine Learning based approach where a cascade function is trained with set of input data. OpenCV contains many pre-trained classifiers for face, eyes, smiles, etc..

## 
