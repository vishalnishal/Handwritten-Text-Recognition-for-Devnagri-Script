# Handwritten-Text-Recognition-for-Devnagri-Script
This project builds a CNN model from scratch in Google Colab to classify 46 Devanagari characters and digits (92,000 samples, 32×32 grayscale). Dataset is CSV-based (pixels + labels). Includes preprocessing, visualization, training, and evaluation.
📝 Handwritten Devanagari Character Recognition
This project demonstrates handwritten Devanagari script character recognition using Convolutional Neural Networks (CNNs) built from scratch in Google Colab.

The dataset contains 92,000 grayscale images (32×32 pixels) representing 46 Devanagari characters and digits (0–9). Data is provided in a CSV format with pixel values and labels.

📂 Dataset
Source: Computer Vision Research Group, Nepal

Shape: 92000 × 1025

Columns:

character: Devanagari character label

pixel1 … pixel1024: Grayscale pixel values

🚀 Features
Load and preprocess CSV dataset in Colab

Visualize Devanagari handwritten characters

Train/test split and normalization

Build CNN model from scratch using TensorFlow/Keras

Evaluate accuracy and visualize predictions

📖 Project Workflow
Load dataset from CSV

Explore and visualize data samples

Preprocess (reshape, normalize, encode labels)

Train CNN model

Evaluate on test data

Plot sample predictions

🔧 Requirements
Python 3.x

TensorFlow / Keras

NumPy

Pandas

Matplotlib

Install dependencies in Colab or locally:

bash
Copy code
pip install tensorflow pandas matplotlib numpy
▶️ Usage
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/Devanagari-Handwritten-Recognition.git
cd Devanagari-Handwritten-Recognition
Open in Google Colab and run notebook.ipynb

Train the CNN and test on handwritten samples

📊 Results
Achieved high accuracy (>90%) on validation set

Correctly predicts most characters and digits

Misclassifications analyzed via confusion matrix

🙏 Acknowledgements
Dataset: Computer Vision Research Group, Nepal

✨ This project is intended for learning AI/ML and exploring multilingual OCR.
