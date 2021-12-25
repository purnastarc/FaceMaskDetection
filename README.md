Face Mask Detection Model - Detection of face masks in  real-time video streams :
Created a convolutional neural network model with MobileNetV2 architecture in place of the convolutional layer.
The data set used for training the model contains a mixture of “ With Mask” and “With Out Mask” images.
The model achieved an accuracy of 97%.
For real-world usage, the OpenCV library is used to get the region of interest of the face in each frame of the video stream and is inputted into the model.
The trained model then predicts “Mask” or “No-Mask” on the faces in each frame.
The model was provided to the end-users as a web application by integrating it into the Flask web framework.

PROJECT DEMO:
https://user-images.githubusercontent.com/67554595/146230924-ab1e268b-0d90-4b20-88b9-9cc538f87252.mp4

