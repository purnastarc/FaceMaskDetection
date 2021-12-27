Face Mask Detection Model - Detection of face masks in  real-time video streams

DESCRIPTION : Created a Convolutional Neural Network model with MobileNetV2 architecture in place of the convolutional layer.
The data set used for training the model contains a mixture of “ With Mask” and “With Out Mask” images.
The model achieved an accuracy of 97%.
For real-world usage, the OpenCV library is used to get the region of interest of the face in each frame of the video stream and is inputted into the model.
The trained model then predicts “Mask” or “No-Mask” on the faces in each frame.
The model was provided to the end-users as a web application by integrating it into the Flask web framework.

PROJECT DEMO :
https://user-images.githubusercontent.com/67554595/146270233-984b7266-273c-46e2-b4fb-dfdfd72cfc3a.mp4

