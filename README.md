# RockLook - Day 01

## What it does
Detects when you look downward via webcam.
Music plays when you look down. Music pauses when you look up.

## How to run
1. pip install opencv-python mediapipe==0.10.9 pygame
2. Put a music.mp3 file in the folder
3. python day01.py

## What I learned
- Threshold = the trigger point (sensor → threshold → actuator)
- pygame plays audio

## Threshold value used
GAZE_THRESHOLD = -0.05
