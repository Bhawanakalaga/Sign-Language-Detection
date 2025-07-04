# Sign Language Detection System

A real-time sign language recognition prototype leveraging Mediapipe for hand‐landmark extraction and an LSTM classifier to translate gestures into text on the fly.

---

## 📋 Table of Contents

1. [Features](#features)  
2. [Project Structure](#project-structure)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Dependencies](#dependencies)  
6. [Contact](#contact)  
7. [License](#license)

---

## 🔍 Features

- **Data Collection**: Capture hand images for all alphabet gestures (A–Z) via webcam.  
- **Keypoint Extraction**: Use Mediapipe to convert frames into 63‐dimensional landmark arrays.  
- **Model Training**: Train a multi‐layer LSTM network on saved keypoint sequences.  
- **Real-Time Detection**: Load the trained model (JSON + H5) and display predicted letters live.  
- **Easy Extension**: Add new gestures or customize the sequence length and model architecture.

---

## 📁 Project Structure

