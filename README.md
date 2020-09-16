# Tom-and-Jerry
A machine learning model for detecting Tom and Jerry Emotions

Task: To predict the emotion of Tom and Jerry from the frame based on their expression.

Assumptions:

1) Path used is relative path  in Google Colab
2) Environment : Google colab
3) Backend : Tensorflow backend, keras

The steps followed are:
1) Reading the images in train and test directory one by one using cv2 package ,converting them to grayscale and placing  them into a list and then converting that list into Numpy array.
2) Reading the training labels.
3) Training a convolutional neural network with first 30 epochs and then 25 epochs.
4) Fitting the data to trained can.
5) Predicting the test data using the trained CNN.


Key Obervations

Convulational Neural Networks with 25 above epochs are best/enough for fitting the model.
