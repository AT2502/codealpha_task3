Leaf Disease Detection
A deep learning-based project for automated detection and classification of plant leaf diseases from images. This project provides a ready-to-use training script, a web demo interface, and clear instructions for deploying your own disease classifier.

Table of Contents
Project Overview

Features

Requirements

Installation

Usage

Demo

Project Structure

Results

Credits

Project Overview
This repository implements a convolutional neural network (CNN) for detecting and classifying diseases in plant leaves. The solution includes an interactive web demo for uploading images and viewing predicted results.

Features
Image preprocessing and augmentation

CNN training on plant leaf disease datasets

Inference script and Gradio-powered web demo

Easily customizable for your own datasets

Requirements
See requirements.txt for exact versions.

Python 3.8+

TensorFlow or PyTorch (edit as per your code)

numpy, pandas, matplotlib, scikit-learn

gradio (for web interface)

tqdm

Installation
Clone the repository and install dependencies:

bash
git clone https://github.com/YOUR-USERNAME/codealpha_task3.git
cd codealpha_task3
pip install -r requirements.txt
Usage
Train the model:
bash
python train.py
Launch the web demo:
bash
python demo.py
Demo
To test the app, run demo.py and open the provided link in your browser. Upload a leaf image and see predicted disease class probabilities.

Project Structure
text
codealpha_task3/
├── train.py                # Training script
├── demo.py                 # Gradio web interface
├── requirements.txt        # Dependencies
├── README.md               # Project documentation
├── images/                 # Example images and assets
└── ...                     # Additional scripts or models
