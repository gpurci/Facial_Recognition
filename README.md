# Facial_Recognition
Face recognition with deep CNN

DESCRIPTION

Facial recognition is a biometric alternative that measures unique characteristics of a human face. Applications available today include flight check in, tagging friends and family members in photos, and “tailored” advertising. You are a computer vision engineer who needs to develop a face recognition programme with deep convolutional neural networks.

Objective: Use a deep convolutional neural network to perform facial recognition using Keras.

Dataset Details:

ORL face database composed of 400 images of size 112 x 92. There are 20 people, 20 images per person. The images were taken at different times, lighting and facial expressions. The faces are in an upright position in frontal view, with a slight left-right rotation.

Link to the Dataset: https://github.com/gpurci/ORL_faces

Image augmentation Details:
Perform augmentation of image randomly, used 3 function noisy, noisy and rotation, aplied filter wiener.
To perform augmentation call method 'getAugmentFunc' put index of wanted function(0 noisy, 1 noisyAndRotation, 2 Wiener)

Link to class: https://github.com/gpurci/ImageAugmentation
