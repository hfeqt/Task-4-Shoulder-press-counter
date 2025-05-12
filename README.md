# Shoulder Press Counter 

This Python project uses **MediaPipe**, **OpenCV**, and **Pygame** to detect and count shoulder press exercise repetitions using your webcam.

## Objective

Create a real-time shoulder press rep counter by tracking arm movement above the head, similar to a bicep curl tracker.

## Features

- Detects pose landmarks using MediaPipe
- Tracks left shoulder → elbow → wrist angle
- Counts reps based on up and down arm movement
- Displays rep count and stage ("Up" or "Down") on screen
- Plays audio feedback after each completed rep using Pygame

## Requirements

Install dependencies using:

```bash
pip install opencv-python mediapipe pygame numpy# Task-4-Shoulder-press-counter
