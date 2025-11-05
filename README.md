# 🎬 IMDB Sentiment Embeddings

A TensorFlow project that classifies IMDB movie reviews as **positive or negative** using a simple neural network with an **Embedding layer**.

---

## 🚀 Project Overview
This notebook trains a model on the IMDB reviews dataset using:
- `TextVectorization` for tokenization and vocabulary building.
- `Embedding` layer to learn word representations.
- Dense layers for binary classification.
- Visualization of **training vs validation loss and accuracy**.

The model also exports learned embeddings (`vecs.tsv`, `meta.tsv`) for visualization in **TensorFlow Embedding Projector**.

---

## 📊 Training Summary

| Metric | Value (Approx.) |
|:------:|:----------------|
| Training Accuracy | ~86% |
| Validation Accuracy | ~82% |
| Training Loss | ↓ near 0 |
| Validation Loss | ↑ (slight overfitting) |

---

## 🧠 Visualization
The plots below show model performance across epochs:

- **Accuracy vs Epochs**
- **Loss vs Epochs**

![](docs/loss_accuracy_plot.png)

---

## 🧩 Files

| File | Description |
|------|--------------|
| `imdb_sentiment_embeddings.ipynb` | Main training notebook |
| `vecs.tsv`, `meta.tsv` | Word embedding outputs for TensorFlow Projector |
| `requirements.txt` | Dependencies |
| `.gitignore` | Keeps repo clean |
| `LICENSE` | MIT License |

---

## 🧰 Tech Stack

- **Python 3**
- **TensorFlow / Keras**
- **TensorFlow Datasets (IMDB Reviews)**
- **Matplotlib**
- **NumPy**

---

## 🔗 Run it on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ak1ra777/imdb-sentiment-embeddings/blob/main/imdb_sentiment_embeddings.ipynb)

---

## 📜 License
MIT License © 2025 [Ak1ra777](https://github.com/Ak1ra777)
