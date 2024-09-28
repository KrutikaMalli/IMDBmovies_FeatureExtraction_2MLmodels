# IMDBmovies_FeatureExtraction_2MLmodels

For this notebook, I have used IMDBmovies dataset ( note: complete dataset is not utilized for this, just first 15,000 rows)

At the end of the notebook, you can find 2 trained models that predict sentiment based on the movie reviews, along with insights into their respective performances measured by accuracy and confusion matrices.

**Work in progress, new techniques are yet to be added to this notebook**.

1) Workflow: The code follows a clear pipeline for sentiment analysis, starting from loading and preprocessing the dataset, through feature extraction, to model training and evaluation.
2) Feature Extraction Methods:
- Bag of Words (BoW)
- TF-IDF
- Word2Vec embeddings
3) Model Training: It uses multiple classifiers (Naive Bayes and Random Forest) to predict sentiments based on the extracted features.
4) Evaluation: Accuracy scores and confusion matrices are generated to assess the performance of each model.
