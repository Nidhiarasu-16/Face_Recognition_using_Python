# Face Detection using OpenCV (Python)

Project Overview : This project implements real-time face detection using Python and OpenCV. It captures live video from a webcam and detects human faces using a Haar Cascade Classifier, drawing bounding boxes around detected faces in each video frame. The project demonstrates practical computer vision concepts such as image preprocessing, object detection, and real-time video processing.

Objective :
  - To detect human faces in real-time using a webcam
  - To apply classical computer vision techniques using OpenCV
  - To understand Haar Cascade–based face detection

Technologies & Tools Used :
  1. Python
  2. OpenCV (cv2)
  3. Haar Cascade Classifier
  4. Webcam (Live Video Input)

How It Works :
  1. Loads a pre-trained Haar Cascade model for frontal face detection
  2. Accesses the system webcam for live video capture
  3. Converts each frame to grayscale to improve detection accuracy
  4. Detects faces using the detectMultiScale() method
  5. Draws bounding boxes around detected faces
  6. Displays the live detection window
  7. Terminates execution when the 'e' key is pressed

Key Parameters Used :
  - scaleFactor = 1.3
      - Controls image scaling for detection flexibility
  - minNeighbors = 5
      - Reduces false positives
  - minSize = (30, 30)
      - Sets minimum face size for detection

Controls :
  - Press e → Exit the live face detection window

Outcome :
  1. Successful real-time detection of human faces from a live webcam feed
  2. Bounding boxes accurately drawn around detected faces
  3. Stable performance using grayscale preprocessing

Future Enhancements :
  1. Face recognition (identity-based detection)
  2. Multiple face tracking
  3. Emotion or expression detection
  4. Dataset-based testing instead of webcam input

Use Case Applications :
  - Surveillance systems
  - Attendance monitoring
  - Human–computer interaction
  - Smart security solutions

📝 License :
  - This project is intended for educational and learning purposes.
