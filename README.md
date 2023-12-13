# Classification automatique d'articles pour Place de marché

## Description:
Ce projet vise à étudier la faisabilité d'un moteur de classification automatique d'articles pour Place de marché, basé sur une image et une description.

## Objectifs:
Démontrer la faisabilité de regrouper automatiquement des produits de même catégorie, en utilisant les descriptions textuelles et les images des produits.
Réaliser une classification supervisée à partir des images, avec un niveau de précision suffisant.
Collecter des produits à base de "champagne" via une API.

## Méthodes:
### Etude de faisabilité:
* Prétraitement des données texte et image
* Extraction de features texte et image
* Réduction en 2 dimensions
* Segmentation en clusters
* Mesure de similarité entre les catégories réelles et les catégories issues de la segmentation en clusters
### Classification supervisée:
* Prétraitement des données image
* Extraction de features image
* Entraînement d'un modèle de classification
* Test du modèle
### Collecte de produits à base de "champagne":
* Appel à l'API
* Filtrage des produits
* Exportation des données dans un fichier CSV

## Outils et bibliothèques:
* Scikit-learn
* TensorFlow, keras
* Python
* Pandas, numpy
* Requests
* nltk
* skimage
* Matplotlib, seaborn, Plotly
* Joblib
