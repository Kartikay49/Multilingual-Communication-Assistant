# Multilingual Communication Assistant (MCA)

> Bridging Language and Cultural Barriers with Real-Time, Context-Aware Translation

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-In%20Progress-yellow)
![Tech](https://img.shields.io/badge/built%20with-Python%20%7C%20React%20%7C%20Whisper%20%7C%20Coqui%20TTS%20%7C%20HuggingFace-blue)

---

## 📌 Project Description

The **Multilingual Communication Assistant (MCA)** is an AI-powered system that enables **real-time speech-to-speech translation**, **accent adaptation**, and **cultural nuance understanding**. Designed to break down linguistic and cultural communication barriers, MCA is ideal for use in education, healthcare, diplomacy, and business.

---

## 🚀 Features

- 🎤 **Speech-to-Text** with Whisper
- 🌍 **Language Translation** using MarianMT (Hugging Face)
- 🗣️ **Text-to-Speech** via Coqui TTS
- 🧠 **Accent Adaptation** using CNNs and Wav2Vec2
- 🤝 **Cultural Context Handling** with rule-based NLP techniques
- 📹 **Non-Verbal Analysis** using OpenCV + MediaPipe (Planned)
- ⚡ **Real-time Performance** via FastAPI & WebRTC (Planned)

---

## 📁 Project Structure

```

Multilingual-Communication-Assistant/
├── backend/                   # FastAPI server (Python)
│   ├── main.py                # Core API logic
│   └── requirements.txt       # Backend dependencies
├── frontend/                  # React.js UI
│   ├── src/                   # React components
│   └── package.json           # Frontend dependencies
├── temp/                      # Temp files (audio processing)
├── .gitignore
└── README.md

````

---

## 🛠️ Tech Stack

### 💻 Backend
- [FastAPI](https://fastapi.tiangolo.com/)
- [Whisper](https://github.com/openai/whisper)
- [MarianMT](https://huggingface.co/Helsinki-NLP/opus-mt-en-es)
- [Coqui TTS](https://github.com/coqui-ai/TTS)
- [PyTorch](https://pytorch.org/)
- [SQLAlchemy](https://www.sqlalchemy.org/)

### 🌐 Frontend
- [React.js](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/) or Bootstrap (your preference)
- [Axios](https://axios-http.com/)

---

## 🧪 How to Run Locally

### 🔧 Prerequisites
- Python 3.9+
- Node.js + npm
- Git
- ffmpeg installed and added to system `PATH`

### ⚙️ Backend Setup

```bash
# Clone the repo
git clone https://github.com/Kartikay49/Multilingual-Communication-Assistant.git
cd Multilingual-Communication-Assistant/backend

# Create virtual environment
python -m venv mca_env
mca_env\Scripts\activate  # On Windows
# or
source mca_env/bin/activate  # On Linux/Mac

# Install dependencies
pip install -r requirements.txt

# Run server
uvicorn main:app --reload
````

### 🌐 Frontend Setup

```bash
cd ../frontend

# Install dependencies
npm install

# Run frontend
npm start
```

---

## 🖼️ Screenshots



> Interface coming soon...

---

## 🔬 Research Reference

This project is part of an academic research initiative.
Read the full paper: [`Multilingual Communication Assistant for Seamless Cross-Cultural Interaction`](./ijarcce.com/papers/multilingual-communication-assistant-bridging-language-and-cultural-barriers-with-real-time-context-aware-translation/)

---

## 📈 Results (Prototype Testing)

| Metric                    | Result     |
| ------------------------- | ---------- |
| Text Translation Accuracy | 92.3% BLEU |
| Speech-to-Speech Accuracy | 87.4%      |
| Accent Classification     | 85.3%      |
| Latency                   | \~298ms    |
| User Satisfaction         | 90.3%      |

---

## 🛡️ License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Authors

* Aryan Gaikwad
* Kartikay Pandey
* Aman Pal

Department of Computer Science and Engineering,
Goel Institute of Technology and Management, Lucknow, India.

---

## 🙌 Acknowledgments

* OpenAI Whisper
* Hugging Face Transformers
* Coqui TTS
* FastAPI
* Mozilla Common Voice

---

## ✉️ Contact

For collaboration or publication inquiries:
📧 [aryan191990@gmail.com](mailto:aryan191990@gmail.com)


