# Real-Time Face Detection with Haar Cascade

This project demonstrates real-time face detection using Haar Cascades in Python with OpenCV. The code captures video from your webcam and detects faces in real-time.

## Prerequisites

- Python 3.x
- OpenCV library

## Code Explanation
- Loading the Haar Cascade Classifier: The CascadeClassifier object is created with a pre-trained Haar cascade XML file for detecting faces.
- Capturing Video: cv2.VideoCapture(0) initializes the webcam. 0 refers to the default camera.
- Processing Frames: Each frame from the webcam is converted to grayscale, and faces are detected using detectMultiScale().
- Drawing Rectangles: Detected faces are highlighted with rectangles.
- Displaying Results: The video stream with detected faces is shown in a window.
- Exiting: The loop exits if the 'q' key is pressed.

## Acknowledgments
- OpenCV for providing the computer vision library.
- Haar Cascade Classifier for the pre-trained models.
  
