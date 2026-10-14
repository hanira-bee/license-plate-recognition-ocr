# Indonesian License Plate Recognition using OCR

A computer vision project for detecting and recognizing Indonesian vehicle license plates using image preprocessing techniques, OpenCV, and Tesseract OCR.

## Overview

This project implements an Optical Character Recognition (OCR) pipeline to read Indonesian vehicle license plates from images.

The system combines several image processing techniques to improve OCR accuracy, including adaptive thresholding, noise removal, contour filtering, image scaling, and ensemble voting.

## Features

- Image upload directly from Google Colab
- Automatic image preprocessing
- Adaptive thresholding (multi-scale)
- Noise and glare removal
- Character contour filtering
- OCR using Tesseract
- Multiple OCR configurations
- Ensemble voting system for improved recognition accuracy
- Indonesian license plate format validation

## Technologies Used

- Python
- OpenCV
- NumPy
- Tesseract OCR
- Pytesseract
- Google Colab

## Workflow

```text
Input Image
     │
     ▼
Image Preprocessing
(Resize, Grayscale, Blur)
     │
     ▼
Adaptive Thresholding
     │
     ▼
Noise Removal
     │
     ▼
OCR Processing
(Tesseract)
     │
     ▼
Plate Format Validation
     │
     ▼
Ensemble Voting
     │
     ▼
Final License Plate Result
```

## Installation
install the required packages:
```sh
pip install opencv-python numpy pytesseract
```

## Install Tesseract OCR
```sh
sudo apt-get update
sudo apt-get install tesseract-ocr
```

## Google Colab
```sh
!apt-get update
!apt-get install tesseract-ocr
!pip install pytesseract
```

## Usage
1. Open the notebook in Google Colab
2. Run all cells
3. Upload a vehicle license plate image
4. The system processes the image automatically
5. The detected plate number will be displayed

## Project Highlights
- Designed for Indonesian vehicle license plates.
- Uses OCR ensemble voting to improve reliability.
- Includes custom validation rules for plate structure.
- Reduces OCR errors caused by glare, noise, and imperfect image quality.

## Future Improvements
- Automatic license plate detection from full vehicle-images.
- Real-time webcam detection.
- YOLO-based plate localization.
- Web application deployment using Flask or Laravel API.
- Accuracy benchmarking on custom datasets.

## Author
- [hanira-bee](https://github.com/hanira-bee) and team
