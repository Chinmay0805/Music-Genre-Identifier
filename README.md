# Music Genre Identifier 🎵

## Overview
The **Music Genre Identifier** is a machine learning project that classifies audio files into different music genres using deep learning techniques. This project utilizes **MFCC (Mel-frequency cepstral coefficients)** for feature extraction and a **Convolutional Neural Network (CNN)** model for classification.

## Features
- 🎧 Supports multiple music genres
- 📊 Extracts audio features using **Librosa**
- 🧠 Uses **CNN** for classification
- 📈 Provides accuracy and loss visualization

## Tech Stack 🛠️
- **Python**
- **TensorFlow / Keras**
- **Librosa** (Feature extraction)
- **Matplotlib & Seaborn** (Visualization)
- **Scikit-learn** (Data processing)
- **Jupyter Notebook** (Development environment)

## Dataset 📂
The dataset consists of audio samples categorized into various music genres. The dataset should be preprocessed to extract MFCC features before training.



## Usage 🎶
1. Prepare the dataset## Installation 🚀
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/music-genre-identifier.git
   ```
2. Navigate to the project directory:
   ```bash
   cd music-genre-identifier
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ``` by extracting MFCC features.
2. Train the CNN model using the extracted features.
3. Evaluate the model performance on test data.
4. Use the trained model to predict music genres for new audio files.

## Model Architecture 🧠
- **Input Layer:** MFCC features from audio
- **Convolutional Layers:** Extract patterns from audio data
- **Fully Connected Layers:** Classify the audio into genres
- **Output Layer:** Softmax activation for genre prediction

## Results 📊
The model achieves high accuracy in predicting music genres, and performance can be further improved with hyperparameter tuning and additional data.


## License 📜
This project is open-source and available under the **MIT License**.

---
🎵 **Enjoy music classification with AI!** 🎵

