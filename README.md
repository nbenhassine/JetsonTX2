# JetsonTX2
# How to install OpenCV (4.1.1) on Jetson TX2?
 The pre-installed OpenCV4Tegra (2.4.13.1) only provided bindings for python2.7.
 When using Python3 on Jetson TX2, the recommended solution is to re-compile OpenCV.
 
 With opencv-4.1.1 properly installed on the Jetson TX2, we could use a python script 
 to capture and display live video from either the Jetson onboard camera, a USB webcam or an IP CAM.

# How to capture and display camera Video with Python3 on Jetson TX2?
I already tried to open Jetson on board camera using newest Jetpack 4.2 and in your python code, nvcamerasrc won't work because is deprecated, instead change to nvarguscamerasrc
