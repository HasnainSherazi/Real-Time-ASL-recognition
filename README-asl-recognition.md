# 🤟 American Sign Language (ASL) Recognition System

A real-time ASL letter recognition application using computer vision — achieving **80% accuracy** on live webcam input.

---

## 📌 Overview

Communication barriers exist for millions of people who use sign language. This project uses computer vision to bridge that gap by recognizing American Sign Language (ASL) hand gestures in real time through a standard webcam — no special hardware needed.

---

## 🎯 Features

- ✅ Real-time ASL letter recognition via webcam
- ✅ 80% accuracy on live input
- ✅ Processes all 26 ASL alphabet letters
- ✅ Lightweight and runs on CPU

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| OpenCV | Webcam capture & image processing |
| Scikit-learn / ML model | Classification |
| NumPy | Array operations |

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/HasnainSherazi/asl-recognition.git
cd asl-recognition

# Install dependencies
pip install opencv-python scikit-learn numpy

# Run the application
python asl_recognition.py
```

> Make sure your webcam is connected. Press `Q` to quit.

---

## 📁 Project Structure

```
asl-recognition/
│
├── asl_recognition.py      # Main application
├── model/                  # Trained model files
├── data/                   # Sample dataset (optional)
└── README.md
```

---

## 📊 Performance

| Metric | Value |
|---|---|
| Accuracy | 80% |
| Input | Live webcam (real-time) |
| Classes | 26 ASL alphabet letters |

---

## 📓 Training Notebook

The model was trained on Kaggle. View the full training process here:  
[![Kaggle](https://img.shields.io/badge/View%20on%20Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/ssyyeedd14)

---

## 🔮 Future Improvements

- [ ] Extend to full words and sentences
- [ ] Add word-level prediction with NLP
- [ ] Deploy as a web app using Flask or Streamlit

---

## 👤 Author

**Syed Muhammad Hasnain Sherazi**  
AI Undergraduate @ CUST  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/syed-muhammad-hasnain-sherazi)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/ssyyeedd14)
[![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-FFD21E?style=flat)](https://huggingface.co/HasnainSherazi)
