# 🤟 Real-Time ASL Letter Recognition System

A real-time **American Sign Language (ASL)** letter recognition application using Computer Vision and Deep Learning — achieving **80% accuracy** on live webcam input.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

---

## 📌 Overview

Communication barriers exist for the millions of people worldwide who use sign language. This project bridges that gap by recognizing **American Sign Language (ASL) hand gestures in real time** through a standard webcam — no special hardware required.

A CNN-based model was trained on an ASL image dataset and deployed in a live webcam application that classifies hand gestures into one of **26 alphabet letters** in real time.

---

## ✨ Features

- ✅ Real-time ASL letter recognition via webcam
- ✅ **80% accuracy** on live input
- ✅ Recognizes all **26 ASL alphabet letters (A–Z)**
- ✅ CNN-based deep learning model (Keras/TensorFlow)
- ✅ Lightweight — runs on standard CPU
- ✅ Instant visual feedback with predicted letter overlay

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| OpenCV | Webcam capture & real-time image processing |
| Keras / TensorFlow | CNN model training & inference |
| NumPy | Array operations |
| Jupyter Notebook | Model training & experimentation |

---

## 📂 Project Structure

```
Real-Time-ASL-recognition/
│
├── App.py                          # Main app — launches webcam & runs inference
├── asl-model-training.ipynb        # Full model training notebook
├── asl_mlp_final_trained.keras     # Trained Keras model
├── asl_weights.h5                  # Saved model weights
├── class_indices_dataset1.json     # Class label mappings (A–Z)
├── convert_model.py                # Model conversion utility
├── model_training_code.txt         # Training code reference
├── keras_extracted/                # Extracted Keras model files
└── requirements.txt                # Python dependencies
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/HasnainSherazi/Real-Time-ASL-recognition.git
cd Real-Time-ASL-recognition
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install opencv-python tensorflow keras numpy
```

### 3. Run the application

```bash
python App.py
```

> 📷 Make sure your **webcam is connected**. Hold an ASL hand sign in front of the camera to see real-time predictions. Press `Q` to quit.

---

## 📊 Model Performance

| Metric | Value |
|---|---|
| Accuracy | **80%** |
| Input | Live webcam (real-time) |
| Classes | 26 ASL alphabet letters (A–Z) |
| Model Type | CNN (Convolutional Neural Network) |
| Framework | Keras / TensorFlow |

---

## 🧠 How It Works

```
Webcam Frame
     │
     ▼
Hand Region Extraction (OpenCV)
     │
     ▼
Image Preprocessing (resize, normalize)
     │
     ▼
CNN Model Inference (Keras)
     │
     ▼
Predicted Letter Overlaid on Frame
```

---

## 📓 Training Notebook

The full model training process — dataset loading, preprocessing, CNN architecture, and evaluation — is available in the notebook:

📒 [`asl-model-training.ipynb`](./asl-model-training.ipynb)

Training was done on the ASL Alphabet dataset. View the Kaggle profile for more:

[![Kaggle](https://img.shields.io/badge/View%20on%20Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/ssyyeedd14)

---

## 🔮 Future Improvements

- [ ] Extend recognition from letters to full **words and sentences**
- [ ] Add NLP layer for word prediction and autocomplete
- [ ] Deploy as a **web app** using Flask or Streamlit
- [ ] Add support for **both hands** simultaneously
- [ ] Improve accuracy with data augmentation and larger datasets

---

## 👤 Author

**Syed Muhammad Hasnain Sherazi**
AI Undergraduate @ CUST, Islamabad

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/syed-muhammad-hasnain-sherazi)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/HasnainSherazi)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/ssyyeedd14)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/HasnainSherazi)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
