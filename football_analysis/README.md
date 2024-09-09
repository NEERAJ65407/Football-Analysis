# Football Analysis Project

## Introduction
The objective of this project is to detect and track players, referees, and footballs in video footage using YOLO, one of the leading AI models for object detection. We will enhance the model's performance through training. Additionally, we'll use K-means clustering to segment and assign players to teams based on the colors of their t-shirts. This allows us to calculate each team's ball possession percentage during a match. To track player movement, we'll apply optical flow for analyzing camera shifts between frames, ensuring precise measurement of player movements. By incorporating perspective transformation, we can account for depth and convert movements from pixels to meters. The project will also calculate player speed and the distance they cover. Overall, this project touches on several key machine learning techniques, solving practical problems, and is ideal for both beginners and experienced engineers.

![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1sFoG-1wmwgAyC-o2-4p6uBcCUVRgFyrF/view?usp=drive_link)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1HS1C1RssB5W4Uvh5FvMxQ0tfFFqqqjaJ/view?usp=drive_link)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas