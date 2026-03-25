# Face Detection Program (Python)

## Overview

This project is a real-time face detection system built using Python and computer vision techniques. It uses OpenCV and pre-trained models to detect human faces in live video streams and images.
I created this project to strengthen my understanding of computer vision and explore how machine learning models can be applied to real-world problems like facial detection.
Include a picture of yourself in 

## Features

* Real-time face detection using webcam
* Detects multiple faces simultaneously
* Fast and efficient processing with OpenCV
* Clean and modular Python code

---

## Technologies Used

* Python
* OpenCV
* NumPy

## How It Works

The program uses a pre-trained Haar Cascade classifier from OpenCV to identify faces in each frame of a video stream. Once detected, bounding boxes are drawn around the faces in real time.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/tanveersubscriptions-stack/FaceDetection.git
cd FaceDetection
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## Input Image Requirement
This program requires a reference image of the user in order to detect their face.

- Add a clear image of your face to the project folder  
- Rename the image to: `reference.jpg` (or update the filename in the code accordingly if image file name is changed)  
- Make sure your face is clearly visible and well-lit  

The program will use this image as a reference to detect and match your face during execution.

## Usage

1. Add your image file ('reference.jpg') to the project directory

2. Run the program:

```bash
python main.py
```

Make sure your webcam is connected. A window will open showing real-time face detection.

## Future Improvements

* Add facial recognition (identify specific individuals)
* Improve accuracy using deep learning models (e.g., CNNs)
* Build a graphical user interface (GUI)
* Optimize performance for faster processing

## What I Learned

* Fundamentals of computer vision
* Working with OpenCV and image processing
* Handling real-time video streams in Python
* Structuring and documenting a technical project

## Author

**Tanveer Sayyad**

