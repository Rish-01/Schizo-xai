# Schizo-xai: Schizophrenia Detection using Wavelet Transform and ResNet-18 🧠 📊

## Overview
This project aims to detect schizophrenia using wavelet transform and a ResNet-18 based classification model. The utilization of wavelet transform allows for a detailed analysis of Electroencephalogram (EEG) data, providing valuable insights into the components of brain signals. You can access my bachelor's thesis [here](https://drive.google.com/file/d/10Ym5TJjOo7lLxuiEEK1GIq8H6MTtUCb3/view?usp=sharing)

## Features
- Schizophrenia detection through EEG data.
- Wavelet transform for feature extraction.
- ResNet-18 for classification.
- GradCAM for explainability on wavelet scalograms.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Rish-01/Schizo-xai.git
   cd Schizo-xai

2. Install Dependencies:
   ```bash
   pip install -r requirements.txt

## Directory Structure
```
.
├── EEG_data
├── image_dir
│   ├── healthy
│   └── schizophrenic
├── model_checkpoints
├── requirements.txt
└── Schizo.ipynb
