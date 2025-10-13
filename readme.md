# Tutoriel pytroch

Introduction aux techniques de deep learning et formation à pytorch et à la logique modulaire.

Ces tutoriels sont directement inspirés de la documentation officielle pytorch, qui est très bien faite: [lien](https://pytorch.org/tutorials/)

En alternative à ce git: parmi les plus jolis cours sur pytorch: [lien](https://uvadlc-notebooks.readthedocs.io/en/latest/)


Attention à bien avoir installer votre machine:
```
conda create -n "torch2025" python=3.12
conda activate "torch2025"
pip install -r requirement2025.txt
```


## 0. Prise en main de pytorch

Comment fonctionne le graphe de calcul? 
- Montrer que les fonctionnalités sont intégrées dans les `tensor` (puis dans les modules)
- Jouer avec ces éléments pour mieux les comprendre... En particulier le gradient!


## 1 Première architecture: le Perceptron Multi-Couches

Comprendre la notion de *module* en pytorch et construire un perceptron multi-couches.


## 2. Architecture à convolution et récurrentes

* Notebook 0: qu'est ce qu'une convolution, comment paramétrer le module, comment jouer avec?
* Notebook 1: première(s) architecture(s) à convolution
   * Cas MNIST: récupération des données
* Notebook 2: introspection des modèles et interprétation post-hoc

## 3. Apprentissage de représentation

Apprendre des représentations continues (et optimisables) pour tous les *objets* qui nous intéressent, en particulier les objets discrets (mots, utilisateurs, produits)

* Notebook 1: Système de recommandation
* Notebook 2: Apprentissage de représentation des mots

## 4. Architectures récurrentes

Idéales pour traiter des séquences et en particulier des séquences de longueurs variables d'un exemple à l'autre.

* Notebook 1: Représentation d'une chaine de caractères


