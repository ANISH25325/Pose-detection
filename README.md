# Pose Detection using OpenCV and MediaPipe

## Overview
This project implements real-time pose detection using OpenCV and MediaPipe. It captures video from the webcam, processes it using MediaPipe's Pose module, and displays detected pose landmarks on the screen.

## Features
- Real-time pose detection using a webcam
- Draws pose landmarks on the detected human body
- Smooth tracking with MediaPipe's pose estimation
- Exits when the 'q' key is pressed

## Requirements
Make sure you have Python installed (preferably 3.6+). Then install the required dependencies:

```sh
pip install opencv-python mediapipe
```

## Usage
Run the script to start real-time pose detection:

```sh
python pose_detection.py
```

## Code Explanation
- **Imports OpenCV and MediaPipe**: Required for video processing and pose detection.
- **Initializes MediaPipe Pose module** with parameters for real-time tracking.
- **Captures video** from the default webcam.
- **Processes each frame** to detect and draw pose landmarks.
- **Displays the processed frame** with landmarks overlaid.
- **Press 'q'** to exit the program.

## Troubleshooting
- If the webcam does not open, ensure no other applications are using it.
- If pose detection is not working, check the camera's lighting conditions.
- Ensure all required packages are installed correctly using `pip list`.

## License
This project is open-source and available for modification and improvement.

