# PROJET LABO - LSD

## Description
Ce projet combine des techniques de Machine Learning, Deep Learning, et de Vision par Ordinateur. Il utilise des bibliothèques populaires comme scikit-learn, TensorFlow, et Mediapipe pour construire un modèle de classification et intégrer des fonctionnalités de traitement d'images, notamment la détection de landmarks. Le projet utilise également des fonctionnalités de gestion de fichiers, de mise en cache des modèles avec pickle, et des outils de visualisation avec matplotlib.

## Bibliothèques Utilisées
- Numpy : Pour les opérations numériques, manipulation de tableaux et gestion des données.
- Pandas : Pour la manipulation de données, l'analyse et le traitement des datasets.
- Scikit-learn :
* train_test_split : Pour diviser le dataset en ensembles d'entraînement et de test.
* RandomForestClassifier : Pour la classification utilisant un modèle d'arbres aléatoires.
* accuracy_score et classification_report : Pour évaluer la performance du modèle.
- Matplotlib : Pour tracer des graphiques et visualiser les résultats.
- OpenCV (cv2) : Pour le traitement d'images et la manipulation vidéo.
- TensorFlow : Pour construire et entraîner des modèles de Deep Learning.
- Mediapipe : Pour la détection des landmarks (visage, mains, pose).
- Pickle : Pour sérialiser (sauvegarder) et désérialiser (charger) des modèles ou des objets Python.
- Warnings : Pour ignorer les avertissements inutiles pendant l'exécution du code.

## Prérequis
Assurez-vous que Python 3.9 ou une version compatible est installée. Les bibliothèques suivantes doivent être installées :

pip install numpy pandas scikit-learn matplotlib opencv-python tensorflow mediapipe

## S'il y a besoin d'un environnement :
conda create -n lds_env python=3.8
conda activate lds_env