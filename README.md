# Legal Case Summarization

Automatically summarize long **Supreme Court of Pakistan** legal judgments using state-of-the-art NLP models (**BART**) with Hugging Face Transformers in Python.

## 📄 Overview
This project builds an **NLP pipeline** to summarize long legal case documents using an **abstractive** approach powered by **BART**, fine-tuned for legal language and style.

## ✨ Features
- **Legal-aware text cleaning and validation** (language detection, gibberish filtering)
- **Abstractive summarization** via Hugging Face **BART**
- **Chunk-wise processing** for large legal documents
- **Evaluation** using ROUGE, BLEU, and semantic similarity (Sentence-Transformers)
- **Optional interactive charts** for analysis (Plotly)
