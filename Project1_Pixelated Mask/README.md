# Pixelated Mask - MediaPipe Face Tracking

A TouchDesigner project that uses MediaPipe for real-time face detection and applies pixelation effects to create an anonymized mask effect.

## About MediaPipe

MediaPipe is Google's open-source framework for building perception pipelines. It provides fast, accurate machine learning solutions for face detection, face mesh tracking, hand tracking, pose estimation, and more. This project leverages MediaPipe's face tracking capabilities to detect and track facial features in real-time.

## Project Structure

- `Pixelated Mask.toe` - Main TouchDesigner project file
- `toxes/` - Contains MediaPipe components and tracking modules
  - `MediaPipe.tox` - Core MediaPipe component
  - `face_tracking.tox` - Face tracking functionality
  - `face_detector.tox` - Face detection module
  - Other tracking and processing components

## Features

- Real-time face detection using MediaPipe
- Pixelation effects applied to detected faces
- Modular component structure for easy customization

## Requirements

- TouchDesigner (2022.31200 or later recommended)
- Webcam or video input source

## Usage

1. Open `Pixelated Mask.toe` in TouchDesigner
2. Allow camera access when prompted
3. The system will automatically detect faces and apply pixelation effects

---

**Technology:** TouchDesigner + MediaPipe
