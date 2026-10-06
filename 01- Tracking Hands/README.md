# Hand Tracking with OpenCV & MediaPipe

A simple real-time hand tracking project using **OpenCV** and **MediaPipe**.

The program captures video from the webcam, detects up to two hands, and displays the 21 landmarks and connections of each detected hand in real time.

## Features

* Real-time webcam capture
* Detection of up to 2 hands
* 21 landmarks per hand
* Hand connection visualization
* Simple and lightweight implementation

## Technologies

* Python
* OpenCV
* MediaPipe
* NumPy

## Installation

Clone the repository and install the dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the program:

```bash
python main.py
```

A window will open showing the webcam feed with the detected hand landmarks.

Press **`Q`** to exit.

## Configuration

The current configuration detects up to two hands:

```python
max_num_hands=2
min_detection_confidence=0.5
min_tracking_confidence=0.5
```

These values can be modified to experiment with detection and tracking performance.

## Purpose

This project was created as a first step into **computer vision and Python libraries**, exploring how OpenCV and MediaPipe can be combined to process webcam input and detect objects in real time.
