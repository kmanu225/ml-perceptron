# Classification de données avec un perceptron

Ce dépôt propose des exemples concrets pour mieux comprendre le perceptron et son utilisation dans la classification de données avec les réseaux de neurones.

## Aperçu

Un **perceptron** est le type le plus simple de réseau de neurones artificiel, souvent utilisé pour des tâches de classification binaire. C’est la base sur laquelle reposent des architectures plus complexes et c’est idéal pour débuter dans le machine learning. Ce projet vient illustrer mon article sur le fonctionnement du perceptron et son implémentation pratique.

## Structure du dépôt

- **activation_function.ipynb**
  - Visualise et compare les fonctions d’activation les plus courantes :
    - **Heaviside (fonction seuil)**
    - **Sigmoïde**
    - **Tanh**
    - **ReLU**
  - Permet de voir en un clin d’œil comment chaque fonction d’activation influence la sortie et les prises de décision dans un réseau de neurones.

- **perceptron.ipynb**
  - Propose une implémentation simple d’un modèle de perceptron avec TensorFlow.
  - Montre comment un perceptron apprend à séparer des points de données grâce à la descente de gradient et la fonction d’activation sigmoïde.
  - Présente toutes les étapes essentielles : chargement des données, entraînement du modèle, prédictions et évaluation.