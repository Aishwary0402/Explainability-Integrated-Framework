# Explainability Integrated Framework

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📄 Overview

The **Explainability Integrated Framework** is a comprehensive toolkit designed to interpret and explain Machine Learning models across multiple modalities. Unlike single-domain tools, this framework integrates explainability techniques for **Audio**, **Text**, and **Video** data into a unified analysis pipeline.

This repository enables researchers and developers to understand *why* their multi-modal models make specific predictions, leveraging techniques like Counterfactual Analysis (for text) and Feature Attribution (for audio/video).

## 🚀 Key Features

### 1. 🎵 Audio Explainability (`Audio_XAI.ipynb`)
* **Goal:** Interpret audio classification models.
* **Techniques:** Visualizes which parts of an audio signal (or spectrogram) contributed most to a prediction.
* **Use Case:** Debugging speech command systems or acoustic event detection.

### 2. 📝 Text Counterfactual Analysis (`TextCF_analysis.ipynb`)
* **Goal:** Explain NLP models by generating counterfactuals (e.g., "What if I changed this word?").
* **Techniques:** Perturbs input text to see how class predictions flip, providing insight into the model's decision boundaries.
* **Use Case:** Analyzing sentiment analysis or spam detection models.

### 3. 🎥 Video Explainability (`Video_2.ipynb`)
* **Goal:** Provide insights into video processing models.
* **Techniques:** likely involves frame-based importance weighting or spatial-temporal feature attribution to identify key moments in a video.
* **Use Case:** Understanding action recognition systems.

### 4. 🔗 Integrated Analysis (`combine.ipynb`)
* A unified notebook that demonstrates how to run these distinct modules together or compares their outputs for multi-modal datasets.

## 🛠️ Tech Stack

* **Language:** Python
* **Environment:** Jupyter Notebooks
* **Core Libraries:** (Inferred)
    * `numpy`, `pandas`, `matplotlib` (Data & Visualization)
    * `librosa` (Audio processing)
    * `opencv-python` (Video processing)
    * `torch` / `tensorflow` (Deep Learning Frameworks)
    * `shap` / `lime` / `textattack` (Explainability libraries)

## 💻 Getting Started

### Prerequisites

Ensure you have Python installed. It is recommended to use a virtual environment.

```bash
git clone [https://github.com/Aishwary0402/Explainability-Integrated-Framework.git](https://github.com/Aishwary0402/Explainability-Integrated-Framework.git)
cd Explainability-Integrated-Framework
