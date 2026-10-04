# Café de la Gare

**Projet développé pour un client**

## Description
Ce projet a été développé pour le client "Café de la Gare". Il s'agit d'une application client/serveur développée en langage C communiquant sur un réseau local (LAN).

## Stack Technique
- **Langage** : C
- **Architecture** : Client / Serveur
- **Réseau** : Sockets, protocole de communication personnalisé (`protocol.h`)

## Installation et Lancement
Pour compiler et exécuter le projet, vous aurez besoin d'un compilateur C (ex: GCC ou MinGW sur Windows).

### Lancement avec le script
1. Clonez ce dépôt.
2. Sous Windows, double-cliquez sur le fichier `run.bat` pour lancer automatiquement l'environnement.

## Arborescence du Projet
```
cafe-de-la-gare/
├── server_main.c    # Logique et gestion du réseau (Serveur)
├── client_main.c    # Logique et affichage (Client)
├── protocol.h       # Définition des structures de paquets
├── run.bat          # Script de lancement pour Windows
└── README.md        # Documentation du projet
```
