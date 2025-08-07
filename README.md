# Processus décisionnels markoviens et apprentissage par renforcement

Projet réalisé dans le cadre du TER (Travail d’Étude et de Recherche) du Master 1 de Modélisation Statistique et Stochastique  
Encadrant : Adrien Richou

## Sujet

Ce projet a pour objectif d'étudier les **processus décisionnels markoviens (MDP)** et leur rôle dans la modélisation des problèmes de décision séquentielle, notamment dans le cadre de l’apprentissage par renforcement.

Une première partie est consacrée à la modélisation  des MDP et des politiques optimales. Une deuxième partie met en œuvre des algorithmes de renforcement dans des environnements simples, permettant d’illustrer les liens entre théorie et pratique.

## Contenu

### Partie 1 – Théorie des MDP

- Définition d’un MDP : espace d’états, espace d’actions, transitions, récompenses
- Politiques déterministes et stochastiques
- Fonctions de valeur, politiques optimales
- Algorithmes de programmation dynamique (valeur et politique)
- Critères de performance (gain total, gain espéré actualisé)

### Partie 2 – Application à l’apprentissage par renforcement

- Présentation de l’environnement Gymnasium
- Implémentation du **Q-learning**
- Étude de convergence de la politique optimale
- Influence du nombre d’épisodes, aléas, hyperparamètres
- Extension à un environnement modifié avec téléporteur

## Outils

- Python  
- Jupyter Notebook  
- Bibliothèques : `gymnasium`, `numpy`, `matplotlib`

