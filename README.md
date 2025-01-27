# Language-Recognition
This project focuses on language recognition, with a particular emphasis on low-resource languages. It leverages a combination of high-resource datasets (e.g., WiLI-2018) and low-resource datasets (Bible texts from ScriptureEarth) to develop and evaluate models for text classification.

Key Features:

•	Datasets:
\n•	High-resource: 22 languages, preprocessed from the WiLI-2018 dataset.
\n•	Low-resource: 25 languages, sourced and preprocessed from ScriptureEarth.
\n•	Preprocessing:
\n•	Text cleaning (removal of punctuation, numbers, whitespaces, and more).
\n•	Sentence segmentation and merging into a unified format.
\n•	Model Architecture:
\n•	Doc2Vec for feature extraction.
\n•	Bi-LSTM combined with a linear layer for text classification.
\n•	Results:
\n•	High accuracy achieved on both high- and low-resource datasets.
\n•	Detailed performance metrics for various scenarios (e.g., excluding certain languages).
\n
This repository contains the code, preprocessing scripts, and trained models for researchers and developers interested in improving language recognition, especially for underrepresented languages.
