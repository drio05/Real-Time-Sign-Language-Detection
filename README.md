## Project Name

Real Time Sign Langauge Dectection

## Domain

Machine Learning

## About Project
Today, around one million people use American Sign Language as their mode of communication according to the Communication Service for the Deaf. Automated two way communication between sign language and text/speech is an unsolved problem globally. We as a team are trying to tackle this issue by the use of Image Processing in real time, in which the machine sees the signs being made by a person and interprets it into the well-understood English language. We make use of Computer Vision and Supervised Model Training

## Tech Stack 

OpenCV, Python, Anaconda, Jupyter Notebook, TensorFlow.

## Team Members

1. Dhanraj Chowdhury
2. Satish Ranjan Das

## Weekly Report
### Week 1
Configured all the required software and got past all the compatibility issues.<br>
Set up the image capture program to collect images for the dataset.
### Week 2
Labelled the collected images by applying bounding boxes to the hand symbols.<br>
Set up the pre-trained training model from TensorFlow GitHub repo, and set up some of the code required to alter the configuration of the pre-trained training model in order to match our requirements.
### Week 3
Finished collecting all the images and made a dataset of over 1300 pictures for 14 signs.<br>
Trained our model using transfer learning with a mean precision of almost 79% in the first attempt.<br>
Fine tuned the model and successfully tested it with all the trained signs.<br>
The model is ready for real time detection.

## References
https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html <br>
https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md <br>
https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html <br>
