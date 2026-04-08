# 🎤 Speech Recognition System using MFCC and Machine Learning

## 📌 Introduction
This project implements a speech recognition system using Mel Frequency Cepstral Coefficients (MFCC) and a Machine Learning model. The system converts spoken words into text by extracting features from speech signals and classifying them using a Support Vector Machine (SVM).

---

## 🚀 Features
- Speech-to-text recognition  
- MFCC feature extraction  
- Machine learning classification (SVM)  
- Waveform visualization  
- Multiple word recognition  
- Google Colab implementation  

---

## 🧠 Concepts Used
- Digital Signal Processing (DSP)  
- Speech Signal Processing  
- MFCC Feature Extraction  
- Machine Learning (SVM)  
- Pattern Recognition  

---

## 🛠 Libraries Used
- numpy  
- librosa  
- matplotlib  
- scikit-learn  
- os  
- google.colab  

---

## 📁 Dataset Structure

```
speech_dataset/
   hello/
      hello1.wav
      hello2.wav

   yes/
      yes1.wav

   no/
      no1.wav
```

Each folder represents one word.

---

## ⚙️ Installation

Install required libraries:

```
pip install librosa soundfile scikit-learn matplotlib
```

---

## ▶️ Implementation Steps

1. Collect speech dataset  
2. Load audio files  
3. Extract MFCC features  
4. Create feature vectors  
5. Train SVM model  
6. Test with new speech input  
7. Display recognized word  

---

## 📊 Block Diagram

```
Speech Input
     ↓
Preprocessing
     ↓
MFCC Feature Extraction
     ↓
Feature Vector
     ↓
SVM Model
     ↓
Recognized Word
```

---

## 🎯 Output

```
Model Accuracy: 0.91
Recognized word: hello
```

---

## 📌 Applications
- Voice command systems  
- Speech-to-text applications  
- Smart home automation  
- Assistive technology  
- Robotics control  

---

## 🔮 Future Scope
- Real-time speech recognition  
- Deep learning implementation  
- Large vocabulary recognition  
- Noise reduction techniques  

---

## 👨‍💻 Author
Your Name
# Speech-Recognition-System-using-MFCC-and-Machine-Learning
