# Remote Sensing Image Captioning using CNN-LSTM with Attention

## 📌 Project Description
This project generates natural language captions for remote sensing images using Deep Learning.
The model uses a CNN Encoder and LSTM Decoder with Bahdanau Attention to generate meaningful captions for satellite images.

This helps in automatic analysis of large-scale remote sensing data without manual effort.

---

## 🚀 Features
- CNN Encoder for feature extraction
- LSTM Decoder for caption generation
- Bahdanau Attention mechanism
- GloVe word embeddings
- Trained on RSICD dataset
- Generates human-like captions

---

## 🧠 Model Architecture
CNN Encoder → Attention → LSTM Decoder → Caption

---

## 📂 Dataset
RSICD (Remote Sensing Image Caption Dataset)

---

## 🛠 Technologies Used
- Python
- NumPy
- Deep Learning

---

## ▶ How to Run

```bash
git clone https://github.com/ashishbharskar/RSICD_image_captioning.git
cd RSICD_image_captioning
pip install -r requirements.txt
python train.py
