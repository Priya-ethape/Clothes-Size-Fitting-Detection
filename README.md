# Clothes-Size-Fitting-Detection

This module implements a real-time clothing size estimation and virtual try-on system using human pose landmarks extracted from a video frame. The primary goal of the system is to accurately estimate upper-body clothing dimensions and overlay a clothing image onto a person in a natural and stable manner. 

Pose estimation is used to detect key human body landmarks from an image or video frame. The system relies on MediaPipe Pose, which internally uses the BlazePose deep learning model to identify 33 anatomical landmarks such as shoulders, hips, elbows, and knees.
In this application, pose estimation provides normalized coordinates (x, y, z) of body joints. These landmarks act as the foundation for calculating body measurements such as shoulder width and torso alignment, which are essential for clothing size estimation and placement.

