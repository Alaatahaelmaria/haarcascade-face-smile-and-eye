# haarcascade-face-smile-and-eye
Detect face , smile and eye by haarcascade Using computer vision 
# What are Haar Cascades?
Haar cascade is an algorithm that can detect objects in images, irrespective of their scale in image and location.

This algorithm is not so complex and can run in real-time.
- We can train a haar-cascade detector to detect various objects like cars, bikes, buildings, fruits, etc.

Haar cascade uses the cascading window, and it tries to compute features in every window and classify whether it could be an object. 

Haar cascade works as a classifier. It classifies positive data points → that are part of our detected object and negative data points → that don’t contain our object.

- Haar cascades are fast and can work well in real-time.
- Haar cascade is not as accurate as modern object detection techniques are.
- Haar cascade has a downside. It predicts many false positives.
- Simple to implement, less computing power required.
- Pre-trained Haar Cascades
- 
# The OpenCV library manages a repository containing all popular haar cascades that can be used for:

- Human face detection
- Eye detection
- Nose / Mouth detection
- Vehicle detection

# Haar cascades are XML files that can be used in OpenCV to detect specified objects.

download data from here:https://github.com/opencv/opencv/tree/master/data/haarcascades
