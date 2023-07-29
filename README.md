# Real-Time-Hand-Landmark-Detection✋

This project uses OpenCV and the MediaPipe library to detect and annotate hand landmarks in a live video stream. The code captures frames from the webcam, processes them using MediaPipe Hands to detect hand landmarks, and then visualizes the detected landmarks on the frames.

# Dependencies🧮

To run this project, you need the following libraries:

- [OpenCV](https://github.com/opencv/opencv): A popular Python library for image and video processing.
- [MediaPipe](https://github.com/google/mediapipe): A library developed by Google for detecting and annotating various objects in images and videos.

# How to Use🤔

1. Install Dependencies:
   Before running the code, make sure to install the required libraries. You can use the following commands to install them:

   ```
   pip install opencv-python
   pip install mediapipe
   ```

2. Run the Code:
   After installing the libraries, run the code and activate your webcam. The project uses your default webcam (if you're using a different webcam, change its number in the `cv2.VideoCapture` function).

3. Display Results:
   When the code runs, the results will be displayed as hand landmarks and the frame rate information on the image.

## Configurations🔄

In the code, we used MediaPipe Hands as the module for hand detection. You can adjust the configurations of this module. Some important configurations include:

- `static_image_mode`: If set to True, it accepts a static image as input instead of a live video stream.
- `max_num_hands`: The maximum number of hands allowed to be detected in a frame.
- `min_detection_confidence`: The minimum confidence level required to detect a hand in a frame.
- `min_tracking_confidence`: The minimum confidence level required to continue tracking a hand after its initial detection.

You can modify these configurations based on your needs and change the hand landmark detection behavior.
