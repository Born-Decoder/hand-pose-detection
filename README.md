# Hand Tracking using MediaPipe

This Python script utilizes the MediaPipe library to perform hand tracking in real-time using your webcam.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- Mediapipe (`pip install mediapipe`)

## Usage

1. Clone the repository or download the `hand_tracking.py` file.
2. Install the required libraries using `pip`.
3. Run the script with `python hand_tracking.py`.
4. Position your hand in front of the camera to see the landmarks detected.

## Configuration

- `mode`: Set to `True` for a more detailed hand model.
- `maxHands`: Maximum number of hands to detect.
- `detectionCon`: Minimum confidence threshold for hand detection.
- `modelComplexity`: Model complexity (0, 1, or 2).
- `trackCon`: Minimum confidence threshold for landmark tracking.

## Credits

- [OpenCV](https://opencv.org/)
- [MediaPipe](https://mediapipe.dev/)

