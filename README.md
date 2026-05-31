# Malaria Detection

A deep learning web app that detects malaria from blood sample images using transfer learning. Built with TensorFlow and VGG19, deployed as a Flask application.

## Features

- Automated malaria detection from blood smear images
- Transfer learning using VGG19 pretrained on ImageNet
- Simple image upload interface for instant diagnosis
- High accuracy classification of Parasitized vs Uninfected cells

## Tech Stack

- **Framework** — Flask
- **Deep Learning** — TensorFlow, Keras
- **Model Architecture** — VGG19 (Transfer Learning)
- **Language** — Python
- **Frontend** — HTML, CSS

## Installation

```bash
git clone https://github.com/Bismabashir/Malaria-detection.git
cd Malaria-detection
pip install -r requirements.txt
python app.py
```

Open your browser at `http://127.0.0.1:5000`

## How It Works

1. User uploads a blood sample image through the web interface
2. Image is preprocessed and passed to the VGG19 model
3. Model classifies the sample as Parasitized or Uninfected
4. Result is displayed instantly on the interface

## Dataset

Trained on the publicly available Malaria Cell Images Dataset containing 27,558 cell images equally split between parasitized and uninfected samples.

## Model

- Base model: VGG19 pretrained on ImageNet
- Fine-tuned on malaria cell images
- Binary classification: Parasitized vs Uninfected
