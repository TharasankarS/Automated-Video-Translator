
# 🎥 Automated Video Translator

**Automated Video Translator** is a Python-based system that converts **Malayalam video content to English**, preserving all background music and sound effects. It separates the vocal track, translates speech, synthesizes English audio, and overlays it onto the original video — making it **highly useful for dubbing applications**, especially where maintaining original ambience is crucial.

---

## 👥 Contributors

- Tharasankar S  
- Neethu Anil Jacob  
- Shawn Antony Soby  
- Vineeth Abraham Koshy

---

## ⚙️ Key Features

- **Malayalam Speech Recognition** using `speech_recognition`
- **Voice Separation** using `spleeter` (vocals vs. background)
- **Gender Detection** using a **custom ResNet-based CNN model**
- **Translation** using **Google Cloud Translation API**
- **Text-to-Speech** using `pyttsx3` (gender-specific English voice)
- **Audio/Video Processing** using `ffmpeg`, `moviepy`, `pydub`, `librosa`

---

## 📦 Dependencies & Setup

> ⚠️ **Important Notes:**
> - Use **Python 3.8 – 3.10** (required for spleeter)
> - Install all dependencies required.
> - Ensure that all dependency versions are compatible with Spleeter. Downgrading NumPy and TensorFlow may be required.
> - Set up **Google Cloud Translation API** and add the api key in the MainCode.py
> - Download the **custom gender classification model** from https://drive.google.com/file/d/1qThAxxx-eeDfVzy8hLxA_Tn3Ji2ls_Rc/view?usp=sharing , unzip and save it inside the Backend directory.
> - Make sure all **directory paths** in the code are correct.


## 🚀 How to Run

1. Run app.py in Frontend

2. Upload video in the html and click convert👍
