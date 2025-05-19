# CV-Yolov11

Ce projet utilise YOLOv11 pour détecter et localiser des pigeons, des corbeaux et des mouettes dans des images. Il contient deux notebooks principaux : un pour l'entraînement du modèle et un pour l'évaluation.

# Aperçu du Projet

## Objectif : Détecter et localiser avec précision les pigeons, les corbeaux et les mouettes dans des images.
## Modèle : YOLOv11
## Notebooks :
CV-Train.ipynb : Utilisé pour entraîner le modèle YOLOv11.
CV-Eval.ipynb : Utilisé pour évaluer les performances du modèle entraîné.

Structure du Répertoire
├── CV-Train.ipynb    # Notebook pour l'entraînement du modèle
├── CV-Eval.ipynb     # Notebook pour l'évaluation du modèle
├── data/             # Dossier pour les données (images, annotations, etc.)
│   ├── images/       # Sous-dossier pour les images
│   ├── labels/       # Sous-dossier pour les annotations (si applicable)
│   └── ...           # Autres données ou dossiers nécessaires
├── models/           # Dossier pour sauvegarder les modèles entraînés
├── README.md         # Ce fichier
└── ...               # Autres fichiers ou dossiers

# Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants installés :

- Python 3.x
- PyTorch
- CUDA (si vous utilisez un GPU)
- Autres dépendances (listées dans les notebooks)

# Installation
Clonez ce dépôt :

git clone https://github.com/votre-nom-d'utilisateur/votre-repo.git
cd votre-repo

# Résultats
Les résultats de l'entraînement et de l'évaluation seront affichés dans les notebooks. Les modèles entraînés seront sauvegardés dans le dossier models/.
