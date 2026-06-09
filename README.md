# News Topic Discovery and Interactive Visualization

This project implements a complete unsupervised Natural Language Processing (NLP) pipeline for large-scale news article analysis. The system automatically preprocesses raw text, extracts semantic features, discovers latent document clusters, identifies interpretable topics within each cluster, and provides interactive visualization tools for exploratory analysis.

## Features

* Advanced text preprocessing using spaCy, including tokenization, lemmatization, stop-word removal, and custom vocabulary filtering.
* TF-IDF feature extraction with unigram and bigram representations.
* Dimensionality reduction using PCA for efficient clustering and visualization.
* Automatic cluster discovery using K-Means with elbow-method optimization.
* Two-stage unsupervised analysis:

  * Document clustering with K-Means.
  * Topic modeling within each cluster using Non-Negative Matrix Factorization (NMF).
* Topic quality optimization through coherence-score-based model selection.
* Interactive Dash dashboard for:

  * t-SNE visualization of document clusters.
  * Keyword-based document exploration.
  * Cluster inspection through topic keywords.
* Cluster-level word cloud generation and keyword frequency analysis.

## Technical Stack

* Python
* spaCy
* Scikit-learn
* Gensim
* Dash
* Plotly
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Pipeline

1. Text preprocessing and normalization
2. TF-IDF vectorization
3. PCA dimensionality reduction
4. K-Means clustering
5. t-SNE visualization
6. Cluster-specific NMF topic modeling
7. Coherence-based topic selection
8. Interactive exploration dashboard
9. Keyword frequency and word cloud analysis

## Dataset

The project was developed using the BBC News dataset and can be adapted to other large-scale text corpora.
