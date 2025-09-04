# Road-Lane-Detection-System
This repository implements lane detection for self-driving cars using classical computer vision techniques such as Canny edge detection, Hough transform, and perspective transforms with sliding window search for curved lanes. The system processes videos frame-by-frame and overlays detected lanes in real time.
Overview
This project implements a lane detection system that processes video footage to identify and highlight lane markings on roads. The system uses a combination of computer vision techniques including Canny edge detection, perspective transformation, and a sliding window algorithm to accurately detect lane lines.

# Features
Perspective Transformation: Converts the road view to a bird's-eye view for better lane detection

Sliding Window Detection: Identifies lane pixels using a histogram-based approach

Real-time Processing: Capable of processing video frames efficiently

Visualization: Draws detected lanes on the original video with a transparent overlay

Installation
# Prerequisites
Python 3.7+

OpenCV

NumPy

MoviePy

Jupyter Notebook (for Colab integration)
