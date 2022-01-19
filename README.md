# sketch-based-object-recognition
A CNN Model to predict mouse-drawn doodles with a tkinter GUI developed in 2017 under Prof. Satish Singh at IIIT Allahabad.

# Demo.mov: 
A short video where I test the model with mouse-drawn shapes ranging from a pizza to a banana.

# model.ipynb
Contains the main code for: 
1) Fetching the Google Quickdraw dataset from Google Storage for 10 categories
2) Initializing and training the CNN model (2000 samples for each class, 10 Epochs for training to yield an accuracy of 96% in the final epoch)
3) Saving the model as an .h5 file (also part of the repo) which is used by main.ipynb which has the GUI application where one can draw and predict

# object_recog.h5
Trained Keras model to be used by main.ipynb which contains our GUI tkinter application for drawing and predicting in real time.

# main.ipynb
Main code for launching our tkinter GUI application and drawing and predicting figures in real time.
