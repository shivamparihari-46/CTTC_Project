# Face Detection and Recognition System

## Overview

This project implements a **Face Detection and Recognition System** using Python and OpenCV.
It captures images, trains a model on collected face data, and recognizes faces in real time using a webcam.

## Features

* Collect face images from webcam
* Train a face recognition model
* Detect faces using Haar Cascade
* Recognize known faces in real time

## Technologies Used

* Python
* OpenCV
* NumPy
* TensorFlow / Keras

## Project Structure

```
face-detection/
│
├── collect_data.py        # Capture face images from webcam
├── consolidated_data.py   # Prepare dataset for training
├── face_detection.py      # Train face recognition model
├── recognize.py           # Real-time face recognition
├── haarcascade_frontalface_default.xml
└── README.md
```

## How to Run

1. Install required libraries

```
pip install opencv-python numpy tensorflow
```

2. Collect face images

```
python collect_data.py
```

3. Train the model

```
python face_detection.py
```

4. Run face recognition

```
python recognize.py
```

## Note

The dataset and trained model files are not included in this repository due to large file sizes.

Thanks for visiting❤️