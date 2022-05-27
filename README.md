# CSCIUA 473 Introduction to Machine Learning Capstone Project: Classification Flavor

Spotify released an API that reports the audio features of its songs, such as “tempo” or “energy”. 
A subset of the API containing 50k randomly picked songs and its features was retrieved, including genre labels. 
The goal of this project was to build a prediction model that accurately classified a song to the correct genre based on its features. 
The dataset size was 50k rows (songs) and 18 features (information about the song).

This dataset was processed using imputation with aggregated medians, dummy variables, and encoding. 
The dimensionality reduction models tested were PCA, t-SNE, and Multi-Dimensional Scaling.
The clustering methods tested were kMeans and DBSCAN.
The classifiers tested were Logistic Regression, SVM, Random Forest, and AdaBoost.

This notebook is not a pipeline. Instead, it tests several different possible models.
The best model was determined to be a kMeans clustering model on PCA combined with a Random Forest classifier with an AUC of 0.92 and an accuracy of 92%.

Report and diagrams are available on request.
