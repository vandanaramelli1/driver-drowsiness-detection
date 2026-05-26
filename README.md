# Driver Drowsiness Detection System

A real-time driver monitoring system developed to detect drowsiness using facial landmark detection and computer vision techniques.

## Features

- Eye closure detection using MediaPipe
- Head tilt monitoring for fatigue analysis
- Real-time SMS alert generation using Twilio
- Live webcam-based monitoring system

## Tech Stack

- Python
- OpenCV
- MediaPipe
- Twilio

## How to Run

```bash
pip install mediapipe twilio opencv-python
python drowsiness.py
```

## Project Overview

This project monitors driver alertness using computer vision and facial landmark tracking. The system analyzes eye movement and head position in real time to identify signs of drowsiness. When fatigue is detected continuously for a certain duration, an alert message is generated automatically.

## Future Improvements

- Mobile notification support
- Cloud-based monitoring dashboard
- Driver face recognition
- Voice-based warning system