# 🧠 HASOC 2025 – Offensive Language and Hate Speech Detection

This repository contains the **code, datasets, and experimental setup** used in our submission to **[HASOC 2025 (Hate Speech and Offensive Content Identification)](https://hasocfire.github.io/hasoc/2025/)** shared task.

We developed and evaluated multiple approaches for **offensive language and hate speech detection** across **Hindi (Devanagari + Roman Hindi)** datasets — exploring traditional machine learning, deep learning, and transformer-based architectures.

---

## 📋 Overview

| Category | Description |
|-----------|-------------|
| **Task** | Hate Speech & Offensive Content Detection |
| **Dataset** | HASOC 2025 official dataset (multilingual social media posts) |
| **Languages Covered** | Hindi (Devanagari + Roman) |
| **Approaches Implemented** | • TF-IDF + Classical ML (Random Forest, SVM)<br>• Word2Vec / FastText embeddings + Neural Networks<br>• Transformer-based models (mBERT, XLM-RoBERTa, DistilBERT)<br>• CNNs |

---

## 📈 Approaches Implemented

### 🧩 1. Traditional Machine Learning
- TF-IDF vectorization  
- Models: Random Forest, Support Vector Machine (SVM)

### ⚙️ 2. Deep Learning
- Word2Vec / FastText embeddings  
- Simple Feed-Forward and CNN architectures

### 🤖 3. Transformer Models
- Multilingual BERT (**mBERT**)  
- **XLM-RoBERTa**  
- **DistilBERT**

---

## 🧾 Citation

If you use this work, please cite:

```bibtex
@misc{hasoc2025,
  title        = {HASOC 2025: Hate Speech and Offensive Content Identification},
  howpublished = {\url{https://hasocfire.github.io/hasoc/2025/}},
  note         = {Accessed: 2025-08-18},
  year         = {2025}
}
