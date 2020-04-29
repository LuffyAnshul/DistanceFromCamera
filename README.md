# OpenCV to calculate Distance between Object and Camera
The repository is used to calculate the distance between the camera and object using OpenCV. 


# Using the following libraries
imutil
numpy
cv2

# Code Explaination
The code accepts initially one image with a distance from the user and later on can determine the distance from the camera, the initial image need to be provided with accurate distance.

The triangle similarity goes something like this: Let’s say we have a marker or object with a known width W. We then place this marker some distance D from our camera. We take a picture of our object using our camera and then measure the apparent width in pixels P. This allows us to derive the perceived focal length F of our camera:

F = (P x  D) / W
