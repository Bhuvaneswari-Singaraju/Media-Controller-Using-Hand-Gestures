# Media Player Controller Using Hand Gestures

This project demonstrates how to control media playback on your computer using hand gestures. By leveraging a webcam to track hand movements, the application sends keyboard commands to control media functions such as play/pause, next track, previous track, volume up, and volume down.

## Features

- **Gesture Recognition:** Detects and interprets hand gestures to control media playback.
- **Media Controls:**
  - **1 Finger Raised:** Forward
  - **2 Fingers Raised:** Backward
  - **3 Fingers Raised:** Volume up
  - **4 Fingers Raised:** Volume down
  - **5 Fingers Raised:** Play/Pause
- **Real-time Processing:** Processes video frames from the webcam in real time.

## Technologies Used

- **OpenCV:** For video capture and image processing.
- **MediaPipe:** For hand tracking and landmark detection.
- **PyAutoGUI:** For simulating keyboard inputs.
- **Python 3.7:** Programming language used for implementation.
