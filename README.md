# Face Recognition Project

![Imgur](https://i.imgur.com/clUVutG.gif)

## Overview

This project demonstrates real-time face recognition using Python and the face_recognition library. It captures video from the webcam, detects faces, and compares them with known faces to recognize individuals and display their name respectively. The known faces are stored as face encodings, and the face_recognition library is used for face detection and recognition.

## Features

- Real-time face recognition using webcam
- Comparison of detected faces with known faces
- Drawing rectangles around detected faces

## Dependencies

- Python (>= 3.6)
- OpenCV (cv2)
- face_recognition
- dlib

## Installation

1. Clone the repository: ```git clone https://github.com/BipinNeupane/Face-Detector-AI.git```<br>
```cd Face-Detector-AI```

2. Install the required dependencies:
```pip install opencv-python```<br>
```pip install face-recognition```<br>
```pip install dlib```<br>

3. Run the face recognition script:
The script will use your webcam to capture video and perform real-time face recognition. Detected faces will be compared with the known faces in the `images/` directory.

## How it Works

The face recognition script follows these steps:

1. Loads the known face images from the `images/` directory.
2. Captures video from the webcam using OpenCV.
3. Detects faces in the video frames using the `face_recognition` library.
4. Computes face encodings for the detected faces.
5. Compares the face encodings of the detected faces with the known face encodings.
6. If a match is found, it displays the person's name and draws a rectangle around their face.

## How to add your own faces?
- Click a clear image of yourself showing your face
- Give the photo a name (Name of the person who's in the Photo)
- Save it in ``images/`` folder 
- Run the program and wallah

## Known Issues

- The accuracy of face recognition depends on the quality and variety of the known face images.
- Face recognition may be affected by changes in lighting, angle, or facial expressions.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

