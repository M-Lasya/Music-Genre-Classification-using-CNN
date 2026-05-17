# Music Genre Classification using CNN

This repository contains a deep learning-based Music Genre Classifier built using the GTZAN dataset. The project classifies audio tracks into one of ten music genres using Convolutional Neural Networks (CNNs) and MFCC (Mel Frequency Cepstral Coefficients) feature extraction.

## Project Overview

Music Genre Classification is an important task in the field of Music Information Retrieval (MIR). This project automatically classifies audio tracks into the following genres:

- Blues
- Classical
- Country
- Disco
- Hip-Hop
- Jazz
- Metal
- Pop
- Reggae
- Rock

The model is trained using the GTZAN dataset, which contains 1000 audio tracks, each 30 seconds long and sampled at 22050 Hz.

The system extracts audio features using Librosa, trains a CNN model using TensorFlow/Keras, and provides an interactive prediction interface using Gradio.

---

## Features

- Audio preprocessing and feature extraction using MFCCs
- CNN-based deep learning model for genre classification
- Training and validation performance visualization
- Interactive Gradio interface for predictions
- Genre probability distribution visualization
- Support for testing custom `.wav` audio files

---

## Technologies Used

- Python 3.x
- TensorFlow / Keras
- Librosa
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Gradio
- Jupyter Notebook / Google Colab

---

## Dataset

This project uses the GTZAN Genre Collection Dataset.

Dataset Details:
- 1000 audio tracks
- 10 genres
- 30-second `.wav` files
- Sampling rate: 22050 Hz

Dataset Link:
https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

---

## Project Workflow

1. Data Collection
2. Audio Preprocessing
3. MFCC Feature Extraction
4. CNN Model Training
5. Model Evaluation
6. Genre Prediction
7. Interactive Deployment using Gradio

---

## Model Architecture

The CNN model consists of:

- Convolutional Layers
- Max Pooling Layers
- Batch Normalization
- Dense Layers
- Dropout Layer
- Softmax Output Layer

The model learns audio patterns such as rhythm, timbre, and frequency characteristics to classify music genres effectively.

---

## Usage

### 1. Download and Extract the Dataset

Download the GTZAN dataset from Kaggle:

https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

Extract the dataset into the `data/` folder.

---

### 2. Training the Classifier

If using Google Colab, mount your Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')
```
* Run the music_genre_classifier.ipynb Jupyter Notebook to train and test the classifier.

* data_10.json file will be generated which has MFCC values, mapping, and labels of genres.
---

## License

This project is developed for academic and educational purposes.
