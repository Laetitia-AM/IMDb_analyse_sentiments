# Analyse de Sentiment des Critiques de Films avec Mixture of Experts (MoE)

## Description
Ce projet académique explore la **classification des sentiments** dans les critiques de films IMDb à l'aide d'un modèle **Mixture of Experts (MoE)**. L'objectif est de prédire si une critique est **positive** ou **négative** en utilisant des techniques avancées de NLP.

## Dataset
Le projet utilise le **IMDb Movie Reviews Dataset**, disponible aux sources suivantes :  
- **Dataset original** : [Stanford AI - IMDb Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)  
- **Dataset sur Hugging Face** : [IMDb Dataset](https://huggingface.co/datasets/stanfordnlp/imdb)  
- **Article de référence** : [Learning Word Vectors for Sentiment Analysis (Maas et al., 2011)](https://aclanthology.org/P11-1015.pdf)

Ce dataset contient **50 000 critiques de films**, annotées comme **positives** ou **négatives**, réparties également entre les ensembles d'entraînement et de test.

Pour ce projet on prendra un échantillon de **2 000 critiques** (1 000 positives, 1 000 négatives) pour un traitement rapide.

## Méthodologie
1. **Prétraitement des textes** : tokenization, suppression des stopwords, stemming/lemmatisation.  
2. **Extraction de caractéristiques** :
   - TF-IDF  
   - Word embeddings (Word2Vec, GloVe)  
3. **Modélisation** : entraînement du modèle Mixture of Experts et autres méthodes puis évaluation des performances.

