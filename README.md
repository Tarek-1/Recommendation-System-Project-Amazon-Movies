# Deep Content-Based Music Recommendation System (Audio + Lyrics)
This project demonstrates a music recommendation system built in Python, combining audio features and lyrics embeddings for over 130,000 songs.

Overview
This notebook implements a robust content-based recommendation engine using deep learning (autoencoder) and modern NLP (Sentence Transformers) to create rich song embeddings. It is designed to recommend songs even when some tracks are missing lyrics or metadata.

# Key steps include:

- Collecting and merging audio features (from Spotify datasets) and lyrics (from lyrics.ovh API and Genius/Kaggle datasets)

- Engineering a unified feature set: audio features, dense lyrics embedding, and a has_lyrics flag

- Training an autoencoder neural network to learn compressed, information-rich song representations

- Recommending similar songs based on cosine similarity in the learned embedding space

# Tools Used
- Python (pandas, NumPy)

- scikit-learn

- TensorFlow / Keras

- sentence-transformers

- Google Colab

# Data Sources
- Spotify Audio Features (Kaggle)

- Genius Lyrics (Kaggle)

- lyrics.ovh API

# How to View
You can open or run the notebook in Google Colab.
Just click the "Open in Colab" badge or button at the top of the GitHub notebook page.
