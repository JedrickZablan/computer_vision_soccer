# Computer Vision Soccer/Football Analysis Using YOLO
**Author:** Jedrick Regala Zablan  
**Date Created:** 06/01/2024  

## Project Description

This project leverages YOLO (You Only Look Once) to develop a computer vision system for analyzing soccer games. The system is designed to provide comprehensive insights into player movements and team performance. It records team ball control, assigns players to teams using k-means clustering, and actively tracks the ball and the player with the ball. Additionally, the system tracks the camera movements, monitors the speed of the players, and calculates the total distance traveled by each player throughout the game.

## Directory Guide

### List of Subdirectories in This Directory:

- **camera_movement_estimator/**: Contains modules and scripts related to estimating camera movement.
- **input_videos/**: Contains the input video files used in the project.
- **output_videos/**: Contains the output video files generated by the project.
- **player_ball_assigner/**: Contains scripts and models for assigning player ball possession.
- **speed_and_distance_estimator/**: Contains modules for estimating speed and distance.
- **stubs/**: Placeholder or temporary files used during the project.
- **team_assigner/**: Contains scripts for team assignment tasks.
- **trackers/**: Modules and scripts for tracking objects within the videos.
- **training/**: Contains training scripts and data for models.
- **utils/**: Utility scripts and helper functions used throughout the project.

### List of Files in This Directory:

- **README.md**: This file.
- **main.py**: The main script to run the project.
- **yolo_inference.py**: Script for running YOLO inference on the video data.

