# 🎵 Emotion-Based Music Recommender

An intelligent web application that captures real-time facial expressions using your webcam, detects your current emotion using deep learning, and recommends songs tailored to your mood via YouTube API.

> 👨‍💻 Built using: **Python**, **Streamlit**, **MediaPipe**, **Keras**, **YouTube Data API**

---


## 🧠 How It Works

1. **Webcam Stream**: Captures face and hand landmarks using MediaPipe Holistic.
2. **Emotion Detection**: Uses a pre-trained Keras model to classify emotions.
3. **Song Recommendation**: Fetches songs from YouTube based on the detected emotion + language + artist.
4. **Secure**: Uses `.env` and Streamlit secrets to keep API keys safe.

---

## 📷 Emotions Detected

- Happy
- Sad
- Angry
- Neutral
- Surprised  
(*Model customizable for more labels*)

---

## 🛠️ Tech Stack

| Frontend         | Backend       | ML / AI       | API Integration     |
|------------------|---------------|----------------|----------------------|
| Streamlit        | Python        | Keras          | YouTube Data API     |
| Streamlit WebRTC | MediaPipe     | TensorFlow     | Requests             |

---

## 🔐 API Key Management

- API keys are **not hardcoded**.
- Local `.env` file used for development (excluded via `.gitignore`)
- Streamlit Cloud uses `secrets.toml` for secure API injection

---

## 🧪 Running Locally

### 🔧 Prerequisites

- Python 3.8+
- `pip install -r requirements.txt`

### 📁 Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/shkr3421/Emotion-based-music-recommender.git
   cd Emotion-based-music-recommender
