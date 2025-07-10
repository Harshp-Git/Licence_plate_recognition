# OCR Number Plate Extractor 🔍🚗

A simple Flask web application that uses EasyOCR and OpenCV to extract text (like license plate numbers) from uploaded images.

## 🔧 Features

- Upload an image via web interface
- Automatic detection and cropping of text regions
- Text extraction using EasyOCR
- Displays extracted text on the webpage

## 📁 Project Structure

ocr_webapp/
├── app.py # Flask backend
├── model/
│ └── ocr_model.py # Core OCR logic using EasyOCR + OpenCV
├── static/
│ └── uploads/ # Uploaded images
├── templates/
│ └── index.html # Frontend HTML


## 🚀 Getting Started

1. **Install dependencies**
   ```bash
   pip install flask easyocr opencv-python imutils

2. **Run App**
   ```bash
   python app.py

1. **Open in browser**
   http://127.0.0.1:5000/
