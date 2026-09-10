# About This Project

## Pixelated Mask - Hand Gesture Controlled Pixelation

An interactive TouchDesigner project that creates a dynamic pixelated mask effect controlled by hand gestures. The pixelation is tracked and positioned between your thumb and index finger in real-time.

## How It Works

This project uses MediaPipe's hand tracking to detect your hand landmarks, specifically the thumb and index finger positions. A pixelated mask effect is generated and positioned dynamically between these two fingers, creating an interactive visual that follows your hand movements.

## About MediaPipe

MediaPipe is Google's open-source framework for building perception pipelines. It provides fast, accurate machine learning solutions for:
- Hand tracking and gesture recognition
- Face detection and mesh tracking
- Pose estimation
- Object detection

This project leverages MediaPipe's hand tracking capabilities to precisely track finger positions in real-time, enabling smooth and responsive interaction.

## Project Structure

- `Pixelated Mask.toe` - Main TouchDesigner project file
- `toxes/` - Contains MediaPipe components and tracking modules
  - `MediaPipe.tox` - Core MediaPipe component
  - `hand_tracking.tox` - Hand tracking and landmark detection
  - Other processing components

## Features

- Real-time hand tracking using MediaPipe
- Thumb and index finger landmark detection
- Dynamic pixelation effect positioned between fingers
- Interactive visual feedback

## Requirements

- TouchDesigner (2022.31200 or later recommended)
- Webcam or video input source
- Good lighting for optimal hand tracking

## Usage

1. Open `Pixelated Mask.toe` in TouchDesigner
2. Allow camera access when prompted
3. Show your hand to the camera
4. Bring your thumb and index finger together to create and control the pixelated mask
5. Move your hand to see the effect follow your gesture

---

**Technology:** TouchDesigner + MediaPipe Hand Tracking
