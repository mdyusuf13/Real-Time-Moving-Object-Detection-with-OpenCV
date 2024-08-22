
"Real-Time Moving Object Detection"

Example Output:


![Screenshot 1](![cameraFeed 8_23_2024 1_17_35 AM](https://github.com/user-attachments/assets/abbfbd9a-90b8-409d-a139-e0a52bb5662b)
)


![Screenshot 2](![cameraFeed 8_23_2024 1_20_37 AM](https://github.com/user-attachments/assets/6d112360-880c-4ae6-a8c9-ae788a3644d2)
)


Overview
This project implements a real-time moving object detection system using OpenCV and Python. It leverages a webcam feed to capture video frames and utilizes image processing techniques to detect and highlight moving objects. The system is designed to enhance surveillance and monitoring applications by automating motion tracking.

Features

Real-time object detection using webcam feed.

Grayscale conversion and Gaussian blur for noise reduction.

Frame difference computation for motion detection.

Contour detection for accurate identification and highlighting of moving objects.

Requirements:

Python 3.x
OpenCV (cv2)
imutils (for image resizing)

Installation:

Clone the Repository:


git clone https://github.com/your-username/real-time-moving-object-detection.git
cd real-time-moving-object-detection

Install Required Packages:


pip install opencv-python imutils

Usage

Run the Script:


python moving_object_detection.py

View the Output:

The script will open a window displaying the webcam feed with moving objects highlighted.
Press q to exit the program.
Code Explanation
Webcam Feed: Captures continuous video frames from the webcam.
Grayscale Conversion: Converts frames to grayscale to simplify processing.
Gaussian Blur: Applies a blur to reduce noise and smooth the image.
Frame Difference: Computes the difference between the current frame and the first frame to detect motion.
Contour Detection: Identifies contours in the thresholded image to highlight moving objects.
