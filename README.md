# OC-P9-Predisez-la-demande-en-electricite

Formation Openclassrooms - Projet n°9 - Prédisez la demande en éléctricité - 60 heures

## Prérequis

Pour effectuer ce projet, il a été nécessaire de manipuler les données en Python, connaître la modélisation de type régression linéaire, ainsi que les différentes modélisations de séries temporelles (AR, MA, ARMA, ARIMA, etc.) 

## Mise en situation

Vous êtes employé chez Enercoop, entreprise spécialisée dans les énergies renouvelables. La plupart de ces énergies renouvelables étant intermittentes, il est difficile de prévoir les capacités de production d'électricité. De plus, la demande en électricité des utilisateurs varie au cours du temps, et dépend de paramètres comme la météo (température, luminosité, etc.) Tout le challenge est de mettre en adéquation l'offre et la demande !

## Les données

Ce sont les données journalières à recompiler en données mensuelles.
Sont également fournies les données météo qui seront utilisées pour corriger les données de l'effet température.

## Votre mission

Vous vous concentrerez uniquement sur la prédiction de la demande en électricité.

Corrigez les données de consommation mensuelles de l'effet température (dues au chauffage électrique) en utilisant une régression linéaire.
Effectuez une désaisonnalisation de la consommation que vous aurez obtenue après correction, grâce aux moyennes mobiles.
Effectuez une prévision de la consommation (corrigée de l'effet température) sur un an, en utilisant la méthode de Holt Winters (lissage exponentiel) puis la méthode SARIMA sur la série temporelle.
Pour chaque traitement effectué (correction de l'effet température, désaisonnalisation, etc.), vous présenterez les 2 séries temporelles avant et après traitement, sur un graphique où les deux séries temporelles seront superposées.

