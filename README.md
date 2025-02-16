# Football Analysis Project

## Introduction
The goal of my project was to detect and track players, referees, and footballs in a video using YOLO, one of the best AI object detection models available. I also trained the model to improve its performance. Additionally, I assigned players to teams based on the colors of their t-shirts using KMeans for pixel segmentation and clustering. With this information, I measured a team's ball acquisition percentage in a match. I also used optical flow to measure camera movement between frames, enabling me to accurately track a player's movement. Furthermore, I implemented perspective transformation to represent the scene's depth and perspective, allowing me to measure a player's movement in meters rather than pixels. Finally, I calculated a player's speed and the distance they covered.


![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player



## Requirements
To run this project, following requirements are installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas