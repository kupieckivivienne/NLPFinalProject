# NLPFinalProject: An Analysis of the Relationship Between Music Genre and Happiness in Song Lyrics
NLP Final Project determining a relationship between genre and valence.

Authors: 
Vivienne Kupiecki
Minh Le
Dylan Leddy
Ryan Clark

Python Libraries Used: 
- OpenML (API) 
- Scikit 
- NumPy 
- Pandas 
- NLTk 
- DistilBERT 

Files:
- Baselines and Classification Models 
  - Shows how we formatted our data, set up word2vec embeddings, 
    then fit our data into different baselines and clasffifiers. 
  - Includes Baseline data for both datasets and classification results for: 
    - KNN (K Nearest Neighbors)
    - MLP (Multi-layer Perceptron)
    - LR (Linear Regression)
    - SGD (Linear Classifier, Scikit) 
    - NB (Naive Bayes)
    - Baseline Accuracy 
    - Random Accuracy 
   
- NLP Final Project: LM 
    - Shows how fit our data into language models like BERT in order to attempt 
    to improve accuracy. In this file we ran bert 4 times.  Once with pop as a genre, once without.
    Once with 5 valence bins, once with 2.
