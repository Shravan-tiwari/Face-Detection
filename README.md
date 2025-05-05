# Face Detection Using Haar Cascade in OpenCV

This project demonstrates a simple yet effective method to detect human faces in an image using Haar Cascade Classifiers with OpenCV in Python.

## 🔍 Overview

The script `face.py` performs the following:

* Loads a custom-trained Haar Cascade classifier (`shravan.xml`)
* Reads an input image (`ww.jpg`)
* Converts the image to grayscale
* Detects faces using the classifier
* Draws colored rectangles around detected faces
* Displays the resulting image using OpenCV's GUI functions

## 📂 Files

* `face.py`: Python script to detect faces in an image.
* `shravan.xml`: Custom-trained Haar cascade classifier file for frontal face detection.
* `ww.jpg`: Example input image (not included in repository).

## 🛠 Requirements

* Python 3.x
* OpenCV

Install dependencies:

```bash
pip install opencv-python
```

## 🚀 How to Run

1. Ensure `face.py`, `shravan.xml`, and `ww.jpg` are in the same directory.
2. Execute the script:

```bash
python face.py
```

## 📸 Output

The script opens a window displaying the image with rectangles drawn around any detected faces.

---

Feel free to modify the XML file or the Python script to suit other face detection tasks or datasets.
