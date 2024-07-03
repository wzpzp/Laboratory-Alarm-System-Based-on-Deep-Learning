# Laboratory-Alarm-System-Based-on-Deep-Learning
This article designs a laboratory alarm system based on deep learning algorithms, which is mainly divided into three parts: facial recognition, theft detection, and fall detection. The specific content is as follows:
(1) For all personnel entering the laboratory, perform facial recognition. Use the CenterFace algorithm to detect facial features and contours and determine whether a face exists in the image. Once a face is detected and tracked, the FaceNet algorithm will attempt to compare the detected face with the stored facial features to determine if it is the internal personnel in the laboratory.
(2) For non-laboratory personnel, conduct property theft testing. Using YOLOv5 to detect laboratory objects, if the object moves a large distance or disappears in a short period of time without tracking, search for the presence of someone in the target attachment. Determine whether it is an outsider based on facial recognition results, and if it is an outsider, issue an alarm.
(3) Using YoloPose for human pose recognition, determine if all personnel in the laboratory have experienced falling behavior, and if someone falls, an alarm will sound.

Requirements:
seaborn
numpy
pillow
matplotlib
pyqt5
matplotlib>=3.2.2
numpy>=1.18.5
opencv-python>=4.4.0.40
opencv-contrib-python>=4.4.0.46
Pillow>=7.1.2
pandas>=1.1.4
pyyaml
easydict
scipy
psutil
importlib_metadata
requests
#seaborn>=0.11.0

lap
hub_sdk


