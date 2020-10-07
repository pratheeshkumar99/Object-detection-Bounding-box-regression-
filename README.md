# Object-detection-Bounding-box-regression-
Here I Built a custom Object Detector model to perform object detection via bounding box regression with keras and TensorFlow.
Here I made of use of Transfer learning approach using VGG-16 model (pre-trained on ImageNet) where I basically chopped-off (topmost layer) fully-connected classification layer head from the network and replaced it with a fully-connected layer with four neurons, corresponding to the top-left and bottom-right (x, y)-coordinates, respectively.
Later I trained the model using a loss function called mean-squared error or mean-absolute error on training data that consists of 820 the input images of airplanes and the corresponding bounding box co-ordinates as targets.
After training, we present an input image to our bounding box regressor network upon which the network will then perform a forward pass and then actually predict the output bounding box coordinates of the airplane present in the image.

Please click on the link to download the saved weights.
https://drive.google.com/file/d/1IDXE-FbK-5fCz-YVGXtkuM_gHMFMkOFY/view?usp=sharing
