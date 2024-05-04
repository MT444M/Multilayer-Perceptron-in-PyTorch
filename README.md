# Multilayer-Perceptron-in-PyTorch

#### Description
Ce notebook Jupyter fournit une introduction pratique à l'utilisation de PyTorch pour la construction et l'entraînement d'un perceptron multicouche (MLP) pour résoudre un problème de classification binaire. Le notebook guide l'utilisateur à travers les étapes de génération de données synthétiques, de visualisation des données, de définition du modèle MLP, d'initialisation des paramètres, d'entraînement du modèle, et d'évaluation des performances du modèle.

#### Contenu
1. **Génération de données**: Création d'un ensemble de données synthétiques de 1000 points avec des étiquettes binaires basées sur une condition géométrique spécifique.
2. **Visualisation des données**: Utilisation de matplotlib pour visualiser les données générées et leur répartition en classes.
3. **Définition du modèle MLP**: Construction d'un modèle de perceptron multicouche avec une couche cachée.
4. **Initialisation des paramètres**: Initialisation des poids et des biais du modèle avec des valeurs aléatoires.
5. **Entraînement du modèle**: Implémentation de la boucle d'entraînement utilisant la descente de gradient pour optimiser les paramètres du modèle.
6. **Évaluation du modèle**: Calcul de l'exactitude du modèle sur les ensembles de données d'entraînement, de validation et de test.
7. **Visualisation des résultats de l'entraînement**: Tracé de la fonction de coût au cours des itérations d'entraînement et visualisation des frontières de décision du modèle.

#### Prérequis
- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- IPython
- colorama
- termcolor

#### Installation des dépendances
Pour installer les dépendances nécessaires, exécutez la commande suivante :
```bash
pip install torch numpy matplotlib ipython  termcolor
```

#### Contribution
Les contributions à ce projet sont les bienvenues. Vous pouvez proposer des améliorations ou des corrections en soumettant une issue ou un pull request sur le dépôt GitHub associé à ce projet.

#### Licence
Ce projet est sous licence MIT. Vous pouvez utiliser, copier, modifier et redistribuer le code source et les documents associés sous les termes de cette licence.
