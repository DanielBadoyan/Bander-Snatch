# Projet-info-Bandersnatch-l2
# Installation et Configuration du Projet Bandersnatch

Ce document explique comment configurer et exécuter le projet Bandersnatch.

## 1. Pré-requis

- Python : Version 3.8 ou supérieure. Assurez-vous que Python est installé et accessible depuis la ligne de commande.
- Git : Pour cloner le dépôt (optionnel).
- pip : Inclus avec Python pour gérer les bibliothèques nécessaires.

## 2. Arborescence du projet

Voici l’arborescence du projet :

Projet-info-Bandersnatch-l2/                                                                     
├── app.py 

├──__pycache__/

├── static/  
  ├── style.css
  ├── app.js

├── templates/  
   └── index.html  


- app.py : Le fichier principal pour démarrer le serveur Flask.
- static/ : Contient les fichiers CSS et JavaScript.
- templates/ : Contient les fichiers HTML pour les pages web.

## 3. Installation des dépendances

1. Ouvrez un terminal et placez-vous dans le répertoire du projet.
2. Installez les bibliothèques nécessaires une par une avec les commandes suivantes :

   pip install flask
   pip install googletrans==4.0.0-rc1
   

## 4. Configuration et installation de LLaMA 2

LLaMA 2 est utilisé pour la génération de contenu dans ce projet. Suivez ces étapes :

1. Téléchargez le modèle LLaMA 2 depuis le site officiel de Meta AI ou une source autorisée.
2. Placez le modèle téléchargé dans un dossier accessible, par exemple : project/models/llama2.
3. Assurez-vous que l'emplacement du modèle est correctement configuré dans le code de app.py.

## 5. Lancer l'application

1. Exécutez le fichier app.py :
   
   python app.py
   
2. Ouvrez votre navigateur et accédez à http://127.0.0.1:5000.

## 6. Fonctionnalités principales

- Connexion : Connectez-vous en tant qu'utilisateur ou invité.
- Création d'aventures : Générez des histoires basées sur des thèmes personnalisés.
- Interactivité : Faites des choix pour avancer dans l’histoire.

## 7. Dépendances Python utilisées

- Flask : Framework web pour Python.
- googletrans : Pour la traduction automatique des histoires (version 4.0.0-rc1).
- subprocess : Gère les processus système pour exécuter des commandes liées a l'IA.

## 8. Remarques

- Si vous rencontrez des problèmes, vérifiez que toutes les bibliothèques sont correctement installées.
- Pour toute question ou amélioration, contactez l’équipe de développement.

Bon jeu avec Bandersnatch !
