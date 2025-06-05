# Face Detection Model (Static Images)

This project demonstrates a face detection system using OpenCV and a pre-trained Haar Cascade classifier. It processes image files (not real-time webcam input) to detect faces.

## 📸 Features

- Detects faces in static image files
- Uses Haar Cascade Classifier (`haarcascade_frontalface_default.xml`)
- Outputs images with bounding boxes drawn around detected faces
- Easy to extend for bulk image processing or face cropping

## 🛠️ Requirements

Make sure you have the following installed:

- Python 3.7+
- OpenCV
- Jupyter Notebook (optional, if using `.ipynb` file)

Install required packages using pip:

```bash
pip install opencv-python
```
## 📂 Files
main_code.ipynb — Notebook that processes images and detects faces

haarcascade_frontalface_default.xml — Pre-trained Haar Cascade file for face detection

input_images/ — Directory with sample images (optional)

README.md — Project documentation

Screen Recording 2025-06-05 115403.mp4 — Demo video of model usage

## 🚀 How to Run
Clone the repository:

```bash
Copy
Edit
git clone https://github.com/cjayahansa/face-detection_s.git
cd face-detection_s
Run the notebook or Python script:
```

```bash
Copy
Edit
jupyter notebook main_code.ipynb
The script loads an image, detects faces, and displays/saves the output image.
```

## 🧠 Algorithm Used
Haar Cascade Classifier: A fast object detection method trained to recognize human faces.

# 📹 Demo
# 🎥 Demo video: 
[Face Detection Output](Screen Recording 2025-06-05 115403.mp4)

## 🙋‍♂️ Author
Chamindu Jayahansa

GitHub
