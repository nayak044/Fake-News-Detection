# 📰 Fake News Detection using CNN + BiLSTM + SMOTE

This project presents a robust system for detecting fake news using a **hybrid deep learning model** that integrates **Convolutional Neural Networks (CNN)**, **Bidirectional LSTM (BiLSTM)**, and **SMOTE** (Synthetic Minority Over-sampling Technique) to handle class imbalance. Developed as part of a research initiative at **IIIT Allahabad**, the model achieves a high accuracy of **96.36%** on a real-world dataset.

---

## 📌 Objective

To accurately classify news articles as **real** or **fake** using modern neural architectures while addressing the challenges of class imbalance and limited context understanding.

---

## ⚙️ Key Features

- 🧠 **Model**: CNN for local feature extraction + BiLSTM for capturing bidirectional temporal dependencies.
- 📊 **SMOTE**: Addressed data imbalance for improved model generalization.
- 💬 **Text Preprocessing**: Tokenization, stopword removal, and headline-body separation.
- 📈 **Transfer Learning**: Explored BERT, DistilBERT, and XLNet for further improvement.
- ✅ **Performance**: Achieved up to **99.27% accuracy** on one of the test datasets.

---

## 🗂️ Dataset

- **Primary**: Fake News Challenge dataset from Kaggle.
- **Additional**: Two more publicly available Kaggle datasets for robustness and evaluation.
- All datasets include labeled articles with text content used for classification.

---

## 📁 Project Structure


---

## 🧪 Methodology

1. **Literature Review**: Studied ML-based and DL-based methods including TF-IDF, Naive Bayes, CNN, BiLSTM, and BERT.
2. **Initial Model**: CNN + LSTM achieved ~40% accuracy.
3. **Improvements**:
   - Switched to BiLSTM + CNN → 90% accuracy.
   - Introduced **SMOTE** for class balancing → 96.36% accuracy.
   - Experimented with transfer learning (BERT, DistilBERT, XLNet).
4. **Preprocessing**:
   - Cleaning text: punctuation, digits, special characters removed.
   - Tokenization and stopword removal.
   - Separated headline and body for context-aware processing.

---

## 📊 Results

| Model                | Accuracy  | Precision | Recall | F1-Score |
|---------------------|-----------|-----------|--------|----------|
| CNN + LSTM          | 40%       | -         | -      | -        |
| CNN + BiLSTM        | 90%       | -         | -      | -        |
| CNN + BiLSTM + SMOTE| **96.36%**| 95.69%    | 97.34% | 96.13%   |
| DistilBERT          | 95%       | -         | -      | -        |
| XLNet               | 94%       | -         | -      | -        |

> Performance metrics were best on the hybrid CNN + BiLSTM with SMOTE approach.

---

## 🧩 Challenges

- Class imbalance skewed predictions toward majority class.
- Required extensive text preprocessing for meaningful features.
- Transfer learning models required fine-tuning for dataset-specific nuances.

---

## 🚀 Future Work

- Deploy as a real-time news validation tool.
- Integrate live APIs for continuous monitoring of news content.
- Extend to multilingual and multimodal (image + text) detection.
- Explore continual learning models for evolving fake news patterns.

---

## 🧑‍💻 Authors

- Jatavath Siddhartha Nayak – IIIT Allahabad
- Siddenthi Uday Kumar – IIIT Allahabad
- Kushal Bansal – IIIT Allahabad
- Aditya Khairnar – IIIT Allahabad
- Sushmitha Pothuraju – IIIT Allahabad

---

## 📚 References

- [Fake News Challenge Dataset - Kaggle](https://www.kaggle.com/competitions/fake-news/data)
- Shu et al., "Fake News Detection on Social Media," ACM SIGKDD, 2017.
- Agrawal et al., "Fake News Detection Using ML", IRJET, 2020.

---

> This project supports the ongoing efforts to reduce the spread of misinformation and promote trustworthy digital content.

