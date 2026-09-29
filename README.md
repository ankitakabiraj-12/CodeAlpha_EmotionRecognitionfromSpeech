# CodeAlpha — Emotion Recognition from Speech

A deep learning-based **Speech Emotion Recognition (SER)** system that analyzes human speech audio and classifies it into different emotional categories using the **TESS (Toronto Emotional Speech Set)** dataset.

The project combines **speech signal processing, MFCC feature extraction, and deep learning** to transform raw audio signals into meaningful representations for emotion classification.

---

## 📌 Project Overview

Human speech contains valuable emotional information expressed through tone, pitch, rhythm, intensity, and other acoustic characteristics. This project explores how machine learning and deep learning can be used to identify these emotional patterns automatically from speech.

The system processes speech recordings, extracts **Mel-Frequency Cepstral Coefficients (MFCCs)**, and uses deep learning models to classify the speaker's emotional state.

---

## 🎯 Objective

The main objective of this project is to develop a speech emotion recognition system capable of:

* Processing human speech audio recordings
* Extracting meaningful acoustic features from speech
* Using MFCCs for speech feature representation
* Training deep learning models for emotion classification
* Evaluating model performance using standard classification metrics
* Analyzing how different emotions are represented in speech signals

---

## 🗂️ Dataset

### TESS — Toronto Emotional Speech Set

This project uses the **TESS (Toronto Emotional Speech Set)** dataset for training and evaluation.

The dataset contains speech recordings representing multiple emotional categories, providing a suitable benchmark for speech emotion recognition experiments.

### Emotion Classes

The project works with the following emotion categories:

* Angry
* Disgust
* Fear
* Happy
* Neutral
* Pleasant Surprise
* Sad

The dataset is organized into emotion-specific folders containing `.wav` speech recordings.

---

## 🧠 Methodology

The project follows a complete speech emotion recognition pipeline:

```text
Speech Audio
     ↓
Audio Preprocessing
     ↓
Feature Extraction
     ↓
MFCC Representation
     ↓
Deep Learning Model
     ↓
Emotion Classification
     ↓
Performance Evaluation
```

### 1. Audio Preprocessing

The speech recordings are prepared for model training through audio preprocessing steps such as:

* Loading WAV audio files
* Converting audio into a consistent format
* Normalizing audio signals
* Handling audio duration and input dimensions

### 2. Feature Extraction

**MFCC (Mel-Frequency Cepstral Coefficients)** features are extracted from the speech signals.

MFCCs are widely used in speech processing because they capture important characteristics of the human auditory perception and provide a compact representation of speech.

### 3. Deep Learning

Deep learning models are trained using the extracted speech features to learn patterns associated with different emotional states.

The project explores neural-network-based approaches such as **CNN and LSTM-based architectures** for speech emotion classification.

### 4. Model Evaluation

The trained models are evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help analyze both overall performance and class-wise prediction behavior.

---

## 🛠️ Technologies Used

| Technology         | Purpose                                 |
| ------------------ | --------------------------------------- |
| Python             | Core programming language               |
| Google Colab       | Development and experimentation         |
| Librosa            | Audio processing and feature extraction |
| NumPy              | Numerical computation                   |
| Pandas             | Dataset handling                        |
| Matplotlib         | Data visualization                      |
| Scikit-learn       | Data preprocessing and evaluation       |
| TensorFlow / Keras | Deep learning model development         |
| MFCC               | Speech feature extraction               |
| TESS               | Speech emotion dataset                  |

---

## 📁 Project Structure

```text
CodeAlpha_EmotionRecognitionfromSpeech/
│
├── dataset/
│   ├── YAF_angry/
│   ├── YAF_happy/
│   ├── YAF_neutral/
│   ├── OAF_Sad/
│   └── ...
│
├── CodeAlpha_EmotionRecognitionfromSpeech.ipynb
│
└── README.md
```

> Dataset folders may vary depending on the organization of the TESS recordings used in the project.

---

## 🔬 Key Features

* 🎙️ Speech-based emotion recognition
* 🎵 Audio signal preprocessing
* 📊 MFCC feature extraction
* 🧠 Deep learning-based classification
* 📈 Model performance evaluation
* 🔍 Confusion matrix analysis
* 🗂️ Multi-class emotion classification
* 📓 Complete experimentation through Google Colab

---

## 📊 Expected Workflow

A typical prediction workflow is:

```text
Input Speech
     ↓
Load Audio
     ↓
Preprocess Signal
     ↓
Extract MFCC Features
     ↓
Feed Features to Trained Model
     ↓
Predict Emotion
     ↓
Display Classified Emotion
```

---

## 💡 Learning Outcomes

Through this project, I gained practical experience in:

* Speech signal processing
* Audio data preprocessing
* MFCC-based feature engineering
* Deep learning for audio classification
* CNN/LSTM model development
* Multi-class classification
* Model evaluation and performance analysis
* Working with real-world speech datasets
* Building an end-to-end machine learning workflow

---

## 🚀 Future Improvements

The project can be further extended with:

* Real-time microphone-based emotion recognition
* Spectrogram-based deep learning models
* Hybrid CNN-LSTM architectures
* Transfer learning using pretrained audio models
* Larger and more diverse speech datasets
* Web or mobile-based emotion recognition interface
* Real-time prediction visualization

---

## 📌 Project Purpose

This project was developed as part of the **CodeAlpha Machine Learning Internship/Project Task** to gain practical experience in speech processing, feature engineering, and deep learning-based classification.

---

## 👩‍💻 Author

**Ankita Kabiraj**

BCA Student | Aspiring Web Developer & AI/ML Enthusiast

GitHub: `ankitakabiraj-12`

---

## ⭐ Acknowledgement

This project uses the **Toronto Emotional Speech Set (TESS)** dataset for speech emotion recognition research and experimentation.

---

## 📜 License

This repository is intended for **educational and learning purposes**.
