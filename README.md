# My_twitter

# Projet Réseau Social Étudiant

## Description

Le but de ce projet est de créer un réseau social pour les étudiants de votre promotion, similaire à Twitter en termes de fonctionnalités. Ce réseau social permettra aux étudiants de se connecter, de partager des tweets, de suivre d'autres membres et d'interagir de manière générale, tout en étant responsive et utilisable sur différentes résolutions d'écran grâce à un micro-framework CSS.

## Fonctionnalités

### Compte Membre
- Inscription et connexion
- Édition de profil

### Tweets
- Publication de tweets avec une limite de 140 caractères
- Ajout de hashtags (#) dans les tweets
- Mention de personnes suivies (@)
- Réponse aux tweets
- Retweet des tweets d'autres utilisateurs
- Ajout de photos dans les tweets avec réduction de l'URL
- Recherche de tags

### Interactions Sociales
- Suivi et désuivi de membres
- Affichage des listes de followers et followings
- Consultation et recherche de profils utilisateurs

### Personnalisation
- Choix de thème utilisateur

### Messagerie
- Système de messagerie privée entre utilisateurs

### Interface Utilisateur
- Timeline rafraîchie automatiquement
- Interface responsive utilisant un micro-framework CSS (Skeleton)

## Base de Données

- Schéma relationnel commun pour tous les groupes de la promotion
- Utilisation d'un fichier `common-database.sql` pour la structure de la base de données
- Mots de passe utilisateurs hashés au format “ripemd160” avec un salt commun : “vive le projet tweet_academy”

## Technologies Utilisées
- PHP
- REACT
- Base de données relationnelle : MySQL
