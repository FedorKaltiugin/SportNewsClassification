# 📰 Sport News Classification (Czech)

This project solves the **multi-class classification** of Czech sports news. It compares classical machine learning approaches with modern transformer-based neural networks.

## 📌 Project Overview

The goal was to assign one of 24 sport categories (e.g., fotbal, hokej, tenis) to a news article title.

We implemented two approaches:
1. **TF-IDF + SVM** — fast and effective for small datasets, achieving accuracy of **97.4%**
2. **Fine-tuned BERT (Czert-B-base-cased)** — contextual model with custom classification head, achieving accuracy of **59.8%**

---

## ⚙️ How to Run

> 🧪 Tested on Google Colab. Compatible with local environments too.

1. Clone this repository:
```bash
git clone https://github.com/FedorKaltiugin/SportNewsClassification.git
cd SportNewsClassification
