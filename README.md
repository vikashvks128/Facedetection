# Face detection
This project captures video frames from your computer's default camera and detects faces in real-time using OpenCV and dlib. It draws rectangles around detected faces and displays the count of faces detected in each frame.
Before running the project, ensure you have the following installed:

Python 3.x
OpenCV
dlib
numpy
The video capture device index might need to be adjusted depending on your system. The default is set to 1. If the video feed doesn't show up, change 1 to 0 in the cv2.VideoCapture(1) line.
