# emotion-recognition
A deep learning model, to predict the emotion of a person in an image as happy or sad.

The code for training and testing the model has been shown in the jupyter notebook, with relevant explanation of various steps.

The model itself is stored in the 'model' folder, to load the model onto your device and check use the load_models method from tensorflow.keras.models, and give the path to the downloaded model.
Then use the predict function of the model to get the prediction.

#Please note to resize the image into (256,256) before passing to the model and also convert image from BGR to RGB, if loaded using OpenCV
