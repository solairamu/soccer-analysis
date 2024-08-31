# Soccer Analysis Project

## Introduction
The goal of this project was to detect and track players, referees, and soccer balls in a video. I also trained the model to improve its performance. Additionally, players will be assigned to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. With this information, a team's ball acquisition percentage in a match can be measured. Als, otical flow is used to measure camera movement between frames, enabling us to accurately measure a player's movement. Additionally, I implement perspective transformation to represent the scene's depth and perspective, allowing to measure a player's movement in meters rather than pixels. Finally, player's speed and the distance covered is calculated. 

![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player
