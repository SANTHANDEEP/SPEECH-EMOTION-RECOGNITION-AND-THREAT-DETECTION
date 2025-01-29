# SPEECH-EMOTION-RECOGNITION-AND-THREAT-DETECTION
Natural Language Processing and Deep Learning

# Overview
This repository contains the Speech Emotion Recognition (SER) and Threat Detection project, developed as part of the M.Tech Business Analytics program at VIT Chennai. The project explores the use of deep learning and machine learning techniques to classify emotions in speech and detect potential threats based on tone and sentiment analysis.

# Abstract
Speech Emotion Recognition (SER) is a critical area in natural language processing (NLP) and machine learning, focusing on identifying emotions from speech signals. This project leverages Multi-Layer Perceptron (MLP), Support Vector Machines (SVM), and Mel Frequency Cepstral Coefficients (MFCCs) for feature extraction and classification. Using the RAVDESS dataset, the model is trained to recognize emotions such as happy, sad, angry, fearful, and neutral, achieving an accuracy of 80.2%.
Additionally, the project explores threat detection, identifying aggressive or distressful speech patterns, which can be used in security systems, mental health analysis, and emergency response applications.

# Key Features
Emotion Classification: Detects emotions like happy, sad, angry, fear, neutral using MLP and SVM models.

Threat Detection: Identifies potentially aggressive or distressful speech patterns for security and mental health applications.

Feature Extraction: Uses Mel Frequency Cepstral Coefficients (MFCCs) and pitch analysis.

Data Augmentation: Applies noise injection, stretching, and pitch shifting to improve model robustness.

Deep Learning Models: Utilizes Multi-Layer Perceptron (MLP) and Support Vector Machines (SVM) for classification.

# Dataset
RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
24 actors (12 male, 12 female)
7 emotions: neutral, calm, happy, sad, angry, fearful, disgusted
1,440 speech samples

# Feature Extraction:
MFCCs (Mel Frequency Cepstral Coefficients)

Pitch and spectral analysis

Methodology

Data Preprocessing

Audio files converted into MFCCs and spectrograms.

Applied data augmentation (noise injection, stretching, shifting, pitch modification) to improve robustness.

# Feature Extraction
Used Librosa for extracting MFCCs and pitch-related features.

# Classification Model

Implemented MLP (Multi-Layer Perceptron) with ReLU activation for emotion classification.
Evaluated using cross-validation, accuracy, precision, recall, and F1-score.

# Threat Detection
Identified aggressive speech using sentiment and tone analysis.

Evaluated potential security risks based on emotion intensity.

# Results
Accuracy: 80.2% (MLP-based model for SER).

F1-score: High precision in detecting emotional states.

Threat Detection: Successfully flagged aggressive/distressful speech patterns.

# Repository Contents
📄 Speech_Emotion_Recognition.pdf → Full project report.
📂 Dataset/ → Contains the RAVDESS dataset (not included due to size constraints, refer to official source).
Source code → Source code is provided.

# sample metrics image:
![image](https://github.com/user-attachments/assets/153f9ea2-b36f-46d6-ac0b-63a0149e5070)

