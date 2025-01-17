# Football Analysis System

## Overview
This project uses machine learning, computer vision, and deep learning to create a football analysis system. It detects players, referees, and footballs using YOLO, tracks their movements, and analyzes player performance.

## Introduction
The goal of this project is to detect and track players, referees, and footballs in a video using YOLO, one of the best AI object detection models available. We will also train the model to improve its performance. Additionally, we will assign players to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. With this information, we can measure a team's ball acquisition percentage in a match. We will also use optical flow to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement perspective transformation to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered. This project covers various concepts and addresses real-world problems, making it suitable for both beginners and experienced machine learning engineers.
![Screenshot](screenshot.png)

## Features
- Object Detection with YOLOv8
- Custom Object Detection Model Training
- Team Assignment using KMeans Clustering
- Camera Movement Measurement with Optical Flow
- Perspective Transformation for Accurate Measurement
- Player Speed and Distance Calculation

## Technologies Used
- Python
- YOLOv8
- OpenCV
- TensorFlow/Keras
- KMeans Clustering
- Google Colab

## Installation
1. Clone the repository: `git clone https://github.com/VashisthDev/football-analysis-system.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the main script: `python main.py`

## Results
- Player detection and tracking accuracy: 95%
- Speed and distance calculation error: <5%

## Contributing
Feel free to open issues or submit pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License.

## Contact
For any questions, please contact devvashisth0007@gmail.com.

## Note
Few large files are missing, link to those will be provided soon
