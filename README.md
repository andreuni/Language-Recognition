# Language Recognition

This project focuses on language recognition, with a particular emphasis on low-resource languages. It leverages a combination of **high-resource datasets** (e.g., WiLI-2018) and **low-resource datasets** (Bible texts from ScriptureEarth) to develop and evaluate models for text classification.

## Key Features:

### Datasets:
- **High-resource:** 22 languages, preprocessed from the WiLI-2018 dataset.
- **Low-resource:** 25 languages, sourced and preprocessed from ScriptureEarth.

### Preprocessing:
- Text cleaning (removal of punctuation, numbers, whitespaces, and more).
- Sentence segmentation and merging into a unified format.

### Model Architecture:
- **Doc2Vec** for feature extraction.
- **Bi-LSTM** combined with a linear layer for text classification.

### Results:
- High accuracy achieved on both high- and low-resource datasets.
- Detailed performance metrics for various scenarios (e.g., excluding certain languages).

---

This repository contains the code, preprocessing scripts, and trained models for researchers and developers interested in improving language recognition, especially for underrepresented languages.
