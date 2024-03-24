# Face Detection System

This is a simple face detection system implemented in Python using the OpenCV library. The system detects faces in real-time video captured from a webcam and draws bounding boxes around the detected faces.

## How it Works

The system utilizes the Haar Cascade classifier for face detection provided by OpenCV. It continuously captures video frames from the webcam, converts them to grayscale, and applies the face detection algorithm to detect faces in the frames. Once a face is detected, a bounding box is drawn around it using OpenCV's rectangle drawing function.

## Requirements

- Python
- OpenCV library

## Usage

1. Ensure you have Python and OpenCV installed on your system.
2. Run the provided Python script (`face_detection.py` or any desired filename).
3. The webcam will be activated, and you'll see a window titled "Krupaya Apna Shri-Mukh Dikhaye" displaying the live video feed with bounding boxes around detected faces.

## Code Explanation

- The script initializes a `CascadeClassifier` object with the pre-trained Haar Cascade classifier for face detection.
- It continuously captures frames from the webcam using `VideoCapture`.
- The `detect_bounding_box` function processes each frame by converting it to grayscale and detecting faces using the `detectMultiScale` method of the `CascadeClassifier` object.
- Detected faces are marked with bounding boxes using OpenCV's `rectangle` function.
- The processed frame is displayed in a window titled "Krupaya Apna Shri-Mukh Dikhaye".
- Press 'q' to exit the program.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
