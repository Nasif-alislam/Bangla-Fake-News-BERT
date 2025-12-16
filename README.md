# 🇧🇩 Bengali Fake News Detection using Transformers

## 📌 Project Overview
Misinformation in low-resource languages like Bengali is a growing crisis. This project implements a Deep Learning pipeline to automatically classify news articles as **Authentic** or **Fake**.

Using **Transfer Learning**, I fine-tuned the pre-trained **BanglaBERT** model (based on BERT architecture) to achieve state-of-the-art performance on the **BanFakeNews** dataset.

## 🚀 Key Results
* **Model:** Fine-Tuned `sagorsarker/bangla-bert-base`
* **Accuracy:** ~99% (on test set)
* **F1 Score:** ~0.99
* **Training Time:** < 5 minutes on T4 GPU

## 🛠️ Tech Stack
* **Python**
* **Hugging Face Transformers** (for Model & Tokenization)
* **Pandas** (for Data Engineering)
* **PyTorch** (Backend framework)

## 📂 Dataset
I utilized the **BanFakeNews** dataset, a benchmark dataset for Bengali fake news detection.
* **Preprocessing:** Handled encoding errors (`latin-1`), tokenized to 128 max length, and removed null values.
* **Split:** 80% Training / 20% Testing.

## 💻 How to Run
1.  Download the `.ipynb` file from this repository.
2.  Upload it to **Google Colab**.
3.  Upload the dataset (`data.csv`).
4.  Run all cells to reproduce the training.

---
*Author: Md Nasif Al Islam*
