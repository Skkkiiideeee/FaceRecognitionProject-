# 👁️ Face Recognition System Using OpenCV

A complete Python-based **face recognition system** using **Haar cascade detection**, **OpenCV**, and **LBPH Face Recognizer**. This project was built to capture, train, detect, and recognize faces in real-time using a webcam, ideal for basic identity verification systems.

> ✅ **All code and model training in this repository was developed by me durinng my internship at CTTC, Bhubaneswar.**

---

## 🚀 Features

- 📸 Real-time **face detection** using Haar cascade classifiers  
- 👤 Face dataset generation via webcam  
- 🗂️ Automatic dataset labeling and preprocessing  
- 🧠 Face recognition using OpenCV's **LBPH (Local Binary Pattern Histogram)** algorithm  
- 🪄 Modular scripts for data collection, model training, recognition, and live camera demo

---

## 🧠 Tech Stack

- **Python 3.x**
- **OpenCV** (cv2)
- Haar Cascade Classifier
- LBPH Face Recognizer
- NumPy
- OS / Filesystem utilities

---

## 🗂️ File Structure

| File | Purpose |
|------|---------|
| `collect_data.py` | Captures face images from webcam and stores them in labeled folders |
| `consolidated_data.py` | Prepares face data and trains the LBPH recognizer |
| `recognize.py` | Uses trained model to recognize faces in live feed |
| `face_detect.py` | Simple face detection using Haar cascades |
| `haarcascade_frontalface_default.xml` | Pre-trained OpenCV model for face detection |

---

## 🔧 How to Run

1. **Install dependencies**
```bash
pip install opencv-python numpy
```

2. **Collect face data**
```bash
python collect_data.py
```

3. **Train the face recognition model**
```bash
python consolidated_data.py
```

4. **Recognize faces in real time**
```bash
python recognize.py
```

---

## 📍 Use Cases

- Smart attendance systems  
- Access control in basic IoT projects  
- Face dataset generation for ML models

---

## 🔐 Notes

- This is a local, non-cloud-based system. No personal data is uploaded or shared.  
- You can extend this to work with cloud APIs or integrate with GUI frameworks like Tkinter or PyQt for a user interface.

---

## 🤝 Future Improvements

- Add support for deep learning models (e.g., FaceNet or Dlib)  
- Build a user interface for better interaction  
- Use SQLite or Firebase for user ID-to-name mapping  
- Enhance recognition with confidence threshold and unknown face detection

---

## 👩‍💻 Author

**Sugyani Krishnadarsinee**  
Built for academic exploration and skill demonstration in computer vision and face recognition.
