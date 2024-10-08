# Virtual Mouse Using OpenCV
Hey Everyone, Chaitanya Jagarwal this side...
In this project, we will use the live feed from the webcam to create a virtual mouse using hand tracking.

![xr-7499160_640](https://github.com/user-attachments/assets/7ccb0b51-9fe1-4628-bd18-9d7bdcfcc15a)

## Project Description:
In this project, I am using my hand as a virtual mouse than can do everything that a mouse does without even touching your system. I am using my system's webcam to detect my hands. It will then create a bounding box around my hand and focus on two fingers: The forefinger and the middle finger. The forefinger will act as a cursor and moving it around, we will be moving the cursor around. Now, inorder to successfully click using hand tracking, it detects the distance between the forefinger and the middle finger. If they are joined together, then it will perform a click. 

![ChaitanyaVirtualMouse](https://github.com/user-attachments/assets/5ecd39cd-d0a5-4dfa-bdc0-f2303bbe1c33)

Furthermore, a smoothness factor was added as the movement was shaky.

## Requirements:
The following modules need to be installed for it to work properly:
- OpenCV
- Mediapipe
- Autopy

### OpenCV:
OpenCV is a huge open-source library for computer vision, machine learning, and image processing. OpenCV supports a wide variety of programming languages like Python, C++, Java, etc. It can process images and videos to identify objects, faces, or even the handwriting of a human.

It can be installed using "pip install opencv-python"


### Mediapipe:
MediaPipe is a framework for building multimodal (eg. video, audio, any time series data), cross-platform (i.e. Android, iOS, web, edge devices) applied ML pipelines.

It can be installed using "pip install mediapipe"

### Autopy:
AutoPy is a simple, cross-platform GUI automation library for Python. It includes functions for controlling the keyboard and mouse, finding colours and bitmaps on-screen, and displaying alerts.

It can be installed using "pip install autopy"

## Important Note:
![vr-6770800_640](https://github.com/user-attachments/assets/63eb00bd-5c0f-4a6b-9731-7059e3f1eee2)

I faced alot of dependency issues throughout this project. Some of the issues and their solutions are as follows:
- autopy not installing: This is because autopy currently doesn't support Python versions above 3.8
- webcam not opening: It was a bug in mediapipe and was fixed in latest python versions

Hence, inorder for the project to run smoothly, you need to degrade the Python version to 3.8

### How to Degrade Python Version:

![chatbot-8147907_1280](https://github.com/user-attachments/assets/ce9d5115-ebfb-4c38-8f53-3516051b9cd8)

Follow the following steps:
- Uninstall Python from add/remove programs
- Go to AppData and remove any python folder you see.
- Download Python 3.8 from this link : [Python 3.8](https://www.python.org/downloads/release/python-380/)
- Install it.
- Open command promt and run "pip" inorder to confirm installation.
- Your Python version has been degraded :)



