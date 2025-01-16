# Formation Deep Learning avec CNN pour la classification d'images

## Introduction

Cette formation est axée sur l'apprentissage des **réseaux de neurones convolutifs (CNN)**, avec une application concrète sur des jeux de données d'images. Elle couvre les principes fondamentaux des CNN, de la préparation des données à l'implémentation de modèles de classification pour des jeux de données comme **MNIST** et **GTSRB**.

La formation complète est disponible sur la chaîne YouTube **CNRS - Formation FIDLE** [ici](https://www.youtube.com/@CNRS-FIDLE).

## Objectifs de la formation

- **Principes des Convolutions** : Comprendre l’opération de convolution, cœur du fonctionnement des CNN.
- **Architecture des Réseaux Convolutifs** : Découvrir les différentes couches et leur rôle dans l’extraction des features.
- **Applications des CNN** : Explorer les domaines où ces réseaux excellent, comme la reconnaissance d'images.
- **Travaux Pratiques** : Appliquer les CNN pour des tâches de classification sur des jeux de données comme MNIST (chiffres manuscrits) et GTSRB (panneaux routiers).

## Contenu du dépôt

Ce dépôt contient les fichiers suivants :

### Dossiers

- **GTSRB** : Dataset pour la reconnaissance des panneaux routiers allemands (German Traffic Sign Recognition Benchmark).
  - **[01 - Preparation-of-data.ipynb](./GTSRB/01%20-%20Preparation-of-data.ipynb)** : Analyse et préparation des données GTSRB, y compris la création d'un dataset amélioré.
  - **[02 - First-convolutions.ipynb](./GTSRB/02%20-%20First-convolutions.ipynb)** : Première implémentation de convolutions pour la classification des panneaux routiers.
  - **[03 - Better-convolutions.ipynb](./GTSRB/03%20-%20Better-convolutions.ipynb)** : Optimisation des convolutions et suivi de l'entraînement du modèle.

- **MNIST** : Dataset pour la reconnaissance des chiffres manuscrits.
  - **[02 - CNN-MNIST.ipynb](./MNIST/02%20-%20CNN-MNIST.ipynb)** : Classification des chiffres manuscrits à l'aide d'un CNN, préparation des données, création du modèle, entraînement et évaluation.

### Autres fichiers

- **[README.md](./README.md)** : Ce fichier.

---

Ce projet vous permettra d'acquérir une compréhension pratique et théorique des réseaux de neurones convolutifs, en appliquant les techniques d'apprentissage profond à des tâches de classification d'images.
