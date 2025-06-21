# 🧠 Real-Time Classroom Attention & Emotion Analyzer

This AI-based system monitors *student attention* and *emotional states* in real-time using webcam input, deep learning, and facial landmark analysis. It is built to assist teachers and edtech platforms in evaluating classroom engagement.

---

## 🎯 Project Highlights

- Detects *student emotions* (happy, sad, angry, etc.) using FER
- Tracks *eye aspect ratio (EAR)* to detect attention levels
- Uses *MediaPipe* for precise facial landmark detection
- Visualizes *attention trend over time* using line plots

---

## 🛠 Tech Stack

| Tool / Library | Purpose                                  |
|----------------|-------------------------------------------|
| OpenCV       | Webcam input, frame capture & display     |
| MediaPipe    | Face Mesh for eye & landmark detection    |
| FER          | Emotion prediction from image             |
| Matplotlib   | Plotting attention over time              |
| Pandas       | Data manipulation and trend logging       |
| NumPy        | Mathematical operations                   |
| Google Colab | Development environment                   |

---

## 🧪 Key Steps in Code

1. Load image / webcam frame
2. Detect face mesh using MediaPipe
3. Calculate EAR (eye aspect ratio) from facial landmarks
4. Detect emotion using FER
5. Display live feedback on attention + emotion
6. Plot attention graph using Matplotlib

---

## 🖼 Sample Output

- Emotion: *Angry*
- Attention: *Inattentive (Eyes Closed)*

![FER Output](![image](https://github.com/user-attachments/assets/1699adf9-d8a2-40f2-ae3e-10b8f2991508)
)

---

## 📊 Attention Trend Over Time

Line plot showing student attentiveness during class session:

![Attention Trend](![image](https://github.com/user-attachments/assets/0ea5099b-5f9a-41b1-86f8-92a8ac28988d)
)

---

## 📁 Files in Repo

| File                  | Description                           |
|------------------------|---------------------------------------|
| AttentionEmotion.ipynb | Main Google Colab notebook           |
| output_emotion.png  | Example output showing face mesh       |
| attention_graph.png | Attention tracking plot image          |

---

## 📥 Install Requirements

```bash
pip install opencv-python
pip install mediapipe
pip install fer
pip install matplotlib
