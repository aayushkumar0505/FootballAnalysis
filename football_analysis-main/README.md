# Football Analysis 

## Introduction

I started this project since I am interested in sports analytics and its practicality in generating real-time, data-driven insights that can enhance performance evaluation, strategy development, and fan engagement. For this project, it was essential to differentiate between players, referees, goalkeepers, and the ball itself. For this, YOLO was the best option for an object detection model. To assign players to teams, I checked the colors of their t shirts using Kmeans which uses pixel segmentation and clustering. With this information, we can deduce the possession time for each team, which is valuable information in telling how a game of football is played out.


![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player
