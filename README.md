# Emotion Detection on Faces

A real-time facial emotion detection system using OpenCV and a pre-trained deep learning model. It captures video from your webcam, detects faces using Haar cascades, and predicts emotional expressions like Happy, Sad, Angry, etc.

## 🎯 Features

- Real-time webcam video capture
- Face detection using OpenCV Haar cascade
- Emotion classification (e.g., Angry, Happy, Sad, etc.)
- Bounding box and emotion label overlay on live feed

## 🧠 Technologies Used

- Python 3
- OpenCV (face detection and video stream)
- Keras with TensorFlow backend (emotion prediction model)
- Haar cascades for face detection
- Pre-trained `.h5` model for emotion recognition

## 📁 Project Structure

```
Emotion-Detection-on-Faces/
├── emotions.py                         # Main Python script for detection
├── haarcascade_frontalface_default.xml # Haar cascade for face detection
├── requirements.txt                    # Python dependencies
└── README.md                           # Project documentation
```

> Note: If your model file (`best_model.h5`) is not yet uploaded or intentionally excluded, update this README accordingly once it's added.

## 🔧 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/manasdarak10/Emotion-Detection-on-Faces.git
cd Emotion-Detection-on-Faces
```

### 2. Install dependencies

Make sure Python 3 is installed, then install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python emotions.py
```

> Ensure that your webcam is connected and the Haar cascade file (`haarcascade_frontalface_default.xml`) is in the same directory as `emotions.py`.

## 💡 How It Works

1. Captures video feed from your webcam using OpenCV.
2. Uses Haar cascades to detect faces in each frame.
3. Extracts the face region, resizes it, and feeds it into a pre-trained emotion detection model.
4. Displays the predicted emotion label on the video feed with a bounding box.

## ✅ requirements.txt

```txt
opencv-python
tensorflow
keras
numpy
```

## 📦 Future Enhancements

- Improve emotion prediction accuracy with larger datasets
- Add GUI for better usability
- Extend model to detect multiple faces simultaneously
- Deploy as a web app using Flask/Streamlit

## 👨‍💻 Author

**Manas Darak**  
GitHub: [https://github.com/manasdarak10](https://github.com/manasdarak10)
