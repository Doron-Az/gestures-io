# Gestures IO

Gestures IO is a software program that enables hand gesture detection and recognition using a webcam. It is developed using several popular open-source libraries, including Mediapipe, OpenCV, TensorFlow, and Python.

With Gestures IO, users can conduct a lecture using gestures to the camera and perform several actions on the computer, such as switching between different programs, scrolling through documents, playing songs, and stopping them, and moving slides in a presentation. The software program is designed to be user-friendly and integrates with other applications with an easy-to-use API.

## Features
Real-time hand gesture detection and recognition using Mediapipe and TensorFlow
Ability to recognize multiple hand gestures
Configurable gesture recognition thresholds
Integration with OpenCV for image processing
Real-time training to teach the system new gestures.



https://user-images.githubusercontent.com/86197721/230718789-186b83c5-72ad-4297-ace6-b65fca90c13b.mp4



## installing
1. create a python virtual environment (venv)
2. open terminal and execute: venv/Scripts/activate
3. execute: pip install -r requirements.txt

## running
1. open terminal and "venv/Scripts/activate"
2. execute: python ui.py

## teaching a new gesture
1. press on key "k" continuously while showing the gesture in front of the camera. Record for at least a minute to have 1000-1500 images.
2. open settings
3. click on button 'train', and restart the progran
## how to create a venv manually
1. open terminal in project
2. check python version (must be >= 3)
3. type:
   1. py -m pip install --upgrade pip
   2. py -m pip install --user virtualenv
   3. py -m venv env
   4. then for any command always make sure to execute: .\env\Scripts\activate
   

## Gestures IO can recognize several different gestures, including:

- Fist
- Palm
- Victory sign
- Thumbs up
- Thumbs down
- Okay sign
- Pinch

New gestures can be taught using machine learning as explained above.

## Contact
If you have any questions or feedback, please open an issue on GitHub or email the project owner at doronazulay9@gmail.com

## links
1. https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#installing-virtualenv
