Created a Facemask mask detection model which can detect face mask in real-time video streams. The model is built using convolutional neural network with MobileNetV2 architecture in place of convolutional layer.
The model is trained on the data set obtained from kaggle which is having Mask and WithOut Mask Images.
The trained model is then integrated with Flask web frame work.
The trained model is then used to classify the face region in each frame of the video captured from webcam. The predcition label is then written back to each video frame in real time.
