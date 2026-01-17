# Analyse de Sentiment des Critiques de Films avec Mixture of Experts (MoE)

## Description
Ce projet académique explore la **classification des sentiments** dans les critiques de films IMDb à l'aide d'un modèle **Mixture of Experts (MoE)**. L'objectif est de prédire si une critique est **positive** ou **négative** en utilisant des techniques avancées de NLP.

## Dataset
- **IMDb Movie Reviews Dataset** : 50 000 critiques de films (25 000 positives, 25 000 négatives)  
- Sources : [Stanford AI](https://ai.stanford.edu/~amaas/data/sentiment/) | [Hugging Face](https://huggingface.co/datasets/imdb)  
- Pour ce projet : échantillon de **2 000 critiques** (1 000 positives, 1 000 négatives) pour un traitement rapide.

## Méthodologie
1. **Prétraitement des textes** : tokenization, suppression des stopwords, stemming/lemmatisation.  
2. **Extraction de caractéristiques** :
   - TF-IDF  
   - Word embeddings (Word2Vec, GloVe)  
3. **Modélisation** : entraînement du modèle Mixture of Experts et autres méthodes puis évaluation des performances.

