# Emotion Detection on Faces

Real-time emotion detection using facial expressions. This project captures webcam video, detects faces, and classifies the emotion for each face using a pre-trained Keras/TensorFlow model.

## 🎯 Features

- Real-time webcam video capture
- Face detection using OpenCV Haar cascade
- Emotion classification (e.g., Angry, Happy, Sad, etc.)
- Display of bounding boxes and emotion labels on the video feed

## 🗂️ Project Structure

```
Emotion-Detection-on-Faces/
│
├─ model/
│   └─ best_model.h5                # Pre-trained emotion detection model
│
├─ haarcascade_frontalface_default.xml  # Haar cascade for face detection
│
├─ emotion_detection.py            # Main Python script
│
├─ requirements.txt                # Python dependencies
│
└─ README.md                       # Project documentation
```

## 📋 Requirements

Install dependencies using pip:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1. **Clone the repository**:
```bash
git clone https://github.com/manasdarak10/Emotion-Detection-on-Faces.git
cd Emotion-Detection-on-Faces
```

2. **Install Python dependencies**:
```bash
pip install -r requirements.txt
```

3. **Make sure the following files are present**:
- `model/best_model.h5`
- `haarcascade_frontalface_default.xml`

4. **Run the application**:
```bash
python emotion_detection.py
```

5. **Controls**:
- The webcam will open in a window.
- Emotion labels will appear on detected faces.
- Press `q` to quit the application.

## 🛠️ How It Works

- The script uses OpenCV to access the webcam and detect faces in real-time.
- Detected faces are cropped and preprocessed.
- The pre-trained deep learning model (Keras/TensorFlow) classifies the emotion.
- The result is displayed with bounding boxes and emotion labels on the video stream.

## 💡 Future Improvements

- Add face recognition to identify specific individuals
- Integrate a GUI using Tkinter or Streamlit
- Log emotions with timestamps into a CSV or database
- Extend support for video files and multiple camera inputs

## 📚 References

- OpenCV documentation for face detection
- Keras/TensorFlow for deep learning
- FER-2013 dataset for emotion classification (common training dataset)

## 👤 Author

**Manas Darak**  
GitHub: [https://github.com/manasdarak10](https://github.com/manasdarak10)
