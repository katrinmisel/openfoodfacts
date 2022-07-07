# Préparez des données pour un organisme de santé publique

Analyse basée sur le jeu de données Open Food : https://fr.openfoodfacts.org/
Projet réalisé dans le cadre de la formation OpenClassrooms : Data Scientist parcours Ingenieur IA

L'objectif de cette analyse est de : 

Nettoyer le jeu de données 
* en supprimant les doublons
* en traitant les valeurs manquantes par IterativeImputer, suppression, mise à 0
* en traitant les valeurs aberrantes (IQR, moyenne, médiane) en tenant compte du contexte metier
* réduction de dimension du jeu de données : les variables non pertinentes éliminées

Analyser le jeu de données 
* Réaliser une analyse univariée et bi-variée avec des graphiques 
* Réaliser une méthode d'analyse descriptive : ACP
* Réaliser une méthode d'analyse explicative : ANOVA

Créer un prototype : exemple d'implémentation de l'analyse.

# Librairies

La liste des librairies utilisés se trouvent dans le fichier requirements.txt.

# Fichiers

- notebook_openfood.ipynb : Fichier JupyterNotebook contenant l'inspection, le nettoyage et l'analyse des données
- prototype.ipynb : Fichier JupyterNotebook contenant le prototype (système de filtrage des données alimentaires)
- fr.openfoodfacts.org.products : Jeu de données utilisé pour l'analyse
- openfood_filtered : Jeu de données après nettoyage
