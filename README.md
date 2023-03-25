# seAI : Implémentation d'une IA Python permettant la détection de déchets plastiques dans une image.

Ce projet est une application qui utilise les données stockées dans le fichier data_map.csv pour afficher une carte interactive. Le dossier pycache contient des fichiers générés par Python lors de l'exécution de l'application. 

Le fichier seai.py est une implémentation d'un modèle de classification d'images utilisant le réseau de neurones profonds ResNet50 pré-entraîné. Ce modèle prend en entrée des images de taille 224x224 pixels et prédit la classe de l'image parmi 10 classes possibles.
ResNet50 a été choisi pour sa capacité à extraire des caractéristiques de haut niveau à partir d'images, ce qui en fait un choix populaire pour les tâches de classification d'images. En utilisant un modèle pré-entraîné, cela permet également de réduire considérablement le temps et les ressources nécessaires pour entraîner le modèle.
Le code utilise des bibliothèques populaires de deep learning telles que TensorFlow et Keras pour la mise en œuvre du modèle, ainsi que Pandas pour la manipulation des données d'entrée. Il utilise également des techniques telles que la régularisation pour éviter le surapprentissage et l'augmentation de données pour améliorer la généralisation du modèle.

## Prérequis

Avant de pouvoir exécuter l'application, vous devez avoir les éléments suivants installés sur votre machine :
Python 3.6 ou supérieur.

## Installation

Clonez ce repository sur votre machine : git clone https://github.com/votre-nom/repository-name.git. 
Accédez au répertoire cloné : cd repository-name. 
Installez les dépendances requises : pip install -r requirements.txt.

## Utilisation

Exécutez l'application : python app.py. 
Ouvrez votre navigateur Web et accédez à l'adresse http://localhost:5000 pour afficher la carte.

## Contribuer

Si vous souhaitez contribuer à ce projet, suivez les étapes ci-dessous :

Fork ce repository.  
Créez une branche pour vos modifications : git checkout -b feature/your-feature-name.   
Faites vos modifications et commitez les changements : git commit -m "Description de vos modifications".   
Poussez les modifications vers votre fork : git push origin feature/your-feature-name.   
Ouvrez une pull request vers ce repository?


