# SeriesTracker 

# Description 

Cette application Android permet de consulter les séries TV populaires en utilisant l’API publique EpisoDate. Ce projet a été réalisé dans un contexte pédagogique en guise d’examen avec des contraintes techniques modernes du développement Android. 

 

## Fonctionnalités 

L’utilisateur peut : 

- Parcourir une liste de séries populaires 
- Consulter les détails d’une série 
- Explorer les épisodes disponibles 
 

 img 1 arborescence 

 

## Technologies utilisées 

- Kotlin 
- Jetpack Compose (UI moderne déclarative) 
- Architecture MVVM 
- Hilt (Dagger Hilt) pour l’injection de dépendances 
- Retrofit pour les appels API 
- Coroutines / Flow pour la gestion asynchrone 
 

## Architecture du projet 

Le projet suit le pattern MVVM (Model - View - ViewModel) : 

## Model 
- Gestion des données 
- Appels API (EpisoDate) 
- Data classes 
- View 
- Interfaces utilisateur avec Jetpack Compose 
- Affichage des listes et détails 
- ViewModel 
- Gestion de la logique métier 
- Exposition des états à la UI 
- Gestion des erreurs 
- L’injection de dépendances est assurée par Hilt, ce qui permet une meilleure modularité et testabilité. 


## Structure du projet 
img 2

### Lancement du projet 

*Prérequis* 

- Android Studio installé 
- SDK Android configuré 
- Connexion Internet 
 

## Étapes d’exécution 

*Cloner le projet* : 
git clone https://github.com/davisjunior381/SeriesTracker  
Ouvrir le projet avec Android Studio 
Laisser Gradle synchroniser les dépendances 
Lancer l’application : 
Cliquer sur Run  
Ou utiliser un émulateur / appareil physique Android 
 

Installation via APK 

Un APK debug est disponible dans le dossier : 
/apk/app-debug.apk 
 

Installation : 

Copier l’APK sur un téléphone Android 
Autoriser les sources inconnues 
Installer l’application 
 

API utilisée 

Les données proviennent de l’API publique EpisoDate : 

https://www.episodate.com/api 

Endpoint utilisé : 

/most-popular → récupérer les séries populaires 
/show-details → détails d’une série 
 

Améliorations possibles 

Mode sombre 
Ajout de favoris 
Recherche de séries 
Gestion avancée des erreurs réseau 
 

Auteur 

Ce travail a été fait par un groupe de 03 étudiants en ingénierie informatique (Systèmes d’informations) de l’ESEO : 

NGO NGUI Yvana 
TCHEDJOU Davis 
TCHIEGUE Jenny 
  

 
