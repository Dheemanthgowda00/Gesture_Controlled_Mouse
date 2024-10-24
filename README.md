# Gesture_Controlled_Mouse

This project allows you to control your computer mouse using hand gestures detected through a webcam. Using `mediapipe` for hand tracking and `pyautogui` for mouse control, various gestures such as moving the cursor, clicking (left, right, and double-click), and taking screenshots can be performed seamlessly in real-time.

## Features

- **Move Cursor**: Move the mouse cursor by moving your hand in front of the camera.
- **Left Click**: Perform a left-click with a specific hand gesture.
- **Right Click**: Perform a right-click gesture.
- **Double Click**: Trigger a double-click action with another gesture.
- **Take Screenshot**: Capture a screenshot using a special gesture.

## Requirements

- Python 3.7+
- OpenCV (`cv2`)
- MediaPipe
- PyAutoGUI
- Pynput
- NumPy (for mathematical calculations)
- Custom utility functions (for angle and distance calculations)

## Installation

To install the required dependencies, run:

```bash
pip install opencv-python mediapipe pyautogui pynput numpy
