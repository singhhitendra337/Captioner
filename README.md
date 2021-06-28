# Captioner
Given an image, generates a caption for it using two different neural networks; Convolutional Neural Network (CNN) and Long Short Term Memory Network (LSTM).

It uses transfer learning using ResNet50 model to leverage the model's trained parameters to encode an image to a 2048 feature vector which is then fed into an LSTM to predict a caption based on the features extracted by Xception
