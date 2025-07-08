# FaceRecognitionProject
This project uses Python and OpemCV to perform simple face recogtnition. It compares a known image with an unknown image and attempts to identify if the person in the known image appears in the unknown image.
## Features
-Load and process images using OpenCV
-Detect and compare faces
-Console output for recognition result

## Files
-'face_recognizer.py' - Main Python script that performs face recognition.
-'known.jpg.JPG' - The imame of the known person.
-'unknown.jpg.jpg' - The image that may contain the known person.

## Requirements
- Python 3.15.5
- OpenCV ('opencv-python')
- Optionally: 'face_recognition' and 'dlib' (if using facial encoding and landmark detection)

  ## How to Run
  1. Clone this repo:
     ```bash
     git clone https://github.com/LeeCannon345/FaceRecognitionProject.git
     cd FaceRecognitionProject
  2. Install the required packages:
     bash
     pip install opencv-python
  3. Run the script:
     ```bash
     python face_recognizer.py   

     
