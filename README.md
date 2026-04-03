# 🎙️ Speech-to-Text using Wav2Vec2 (ASR Project)

## 📌 Overview

This project implements an **Automatic Speech Recognition (ASR)** system that converts speech (audio) into text using **Facebook’s Wav2Vec2 model** from Hugging Face Transformers and **SPRINGLab's asr-task-data**.

The pipeline includes:

* Dataset preprocessing
* Vocabulary creation
* Tokenization & feature extraction
* Model training using CTC (Connectionist Temporal Classification)
* Evaluation using Word Error Rate (WER)

---

## 🐍📓 Notebook Link

[Click Here](https://colab.research.google.com/drive/1JzuW9ykhbII9-DAlWof6EDc-q0gutlEz?usp=sharing)

---

## 🚀 Features

* End-to-end speech-to-text pipeline
* Custom vocabulary generation from dataset
* Hugging Face `Wav2Vec2Processor` integration
* Fine-tuning pretrained `facebook/wav2vec2-base`
* Dynamic padding with custom data collator
* Evaluation using WER metric

---

## 🧠 Model Architecture

* **Base Model:** `facebook/wav2vec2-base`
* **Framework:** Hugging Face Transformers
* **Loss Function:** CTC Loss
* **Evaluation Metric:** Word Error Rate (WER)

---

## 📂 Dataset

* Dataset used: [`SPRINGLab/asr-task-data`](https://huggingface.co/datasets/SPRINGLab/asr-task-data)
* Contains:

  * Audio samples
  * Corresponding text transcripts

---

## 📊 Results

* Model performance is evaluated using WER
* Achieved WER: 0.248
* Lower WER indicates better transcription accuracy

---

## 📁 Project Structure

```
├── Speech_To_Text.ipynb   # Main notebook
├── vocab.json             # Generated vocabulary
├── README.md              # Project documentation
```

---
