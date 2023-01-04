# facialRecognition

Needs tweaks:

- on recognition math for better accuracy
- on optimization for re-encoding on new person detection/insertion

FaceRecognition Class has encode function that calls from faceData folder

- folder should be in same path as main.py
- folder should contain images of stored faces
- New person detection should save to same folder (within run-recognition func)
- Ommitted for privacy reasons

Python FR project -

Setup:
Python3
(0) Ensure cmake is installed (if not: pip install cmake)

1. pip install dlib==19.22 (-vvv to show real time progress) [can take a while]
2. pip install opencv-python
3. pip install face_recognition

Possible Issues:
Make sure you are using version of Python where packages have been installed

Notes:

userStore.json is to make note of how many users stored
needed for new file creation annotation
