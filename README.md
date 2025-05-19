# CV-Yolov11

## Description du Projet

Ce projet a pour but de détecter et de localiser des pigeons, des corbeaux et des mouettes dans des images et des vidéos en utilisant le modèle de détection d'objets YOLOv11 (You Only Look Once).  Le projet inclut deux notebooks principaux :

* **CV-Train.ipynb** : Ce notebook est utilisé pour entraîner le modèle YOLOv11 sur un dataset d'images annotées.
* **CV-Eval.ipynb** : Ce notebook est utilisé pour évaluer les performances du modèle entraîné sur des images et des vidéos de test.

## Fonctionnalités

* Détection d'objets en temps réel
* Prise en charge de trois classes d'oiseaux : pigeons, corbeaux et mouettes
* Utilisation de l'architecture YOLOv11
* Entraînement et évaluation du modèle
* Notebooks Jupyter pour une expérimentation et une reproductibilité faciles

## Installation

1.  **Installez les dépendances :**

    Assurez-vous d'avoir installé les dépendances nécessaires, qui peuvent inclure, mais sans s'y limiter :
    * TensorFlow ou PyTorch
    * OpenCV
    * Jupyter Notebook
    * Autres bibliothèques spécifiées dans les notebooks.

2.  **Téléchargez le Dataset :**
    * Si vous utilisez un dataset personnalisé, placez-le dans le répertoire approprié.
    * Si vous utilisez un dataset public, suivez les instructions dans le notebook `CV-Train.ipynb` pour le télécharger et le préparer.

## Utilisation

1.  **Entraînement du Modèle :**
    * Ouvrez le notebook `CV-Train.ipynb` dans Jupyter Notebook.
    * Suivez les instructions dans le notebook pour préparer le dataset, configurer les paramètres d'entraînement et lancer l'entraînement du modèle.

2.  **Évaluation du Modèle :**
    * Ouvrez le notebook `CV-Eval.ipynb` dans Jupyter Notebook.
    * Suivez les instructions dans le notebook pour charger le modèle entraîné, configurer les paramètres d'évaluation et évaluer les performances du modèle sur des images et des vidéos de test.

## Structure du Répertoire

├── CV-Train.ipynb          # Notebook pour l'entraînement du modèle├── CV-Eval.ipynb           # Notebook pour l'évaluation du modèle├── data/                   # Répertoire pour les datasets│   ├── train/              # Dossier pour les images d'entraînement│   └── val/                # Dossier pour les images de validation├── models/                 # Répertoire pour les modèles entraînés├── requirements.txt        # Liste des dépendances├── README.md               # Ce fichier└── ...
## Résultats

Les résultats typiques incluent :

* Courbes de perte d'entraînement
* Métriques d'évaluation (par exemple, mAP)
* Détections visuelles sur des images et des vidéos de test

## Remerciements

* YOLOv11
* L'équipe de recherche qui a créé le dataset utilisé
* Toute autre bibliothèque ou ressource utilisée dans ce projet
