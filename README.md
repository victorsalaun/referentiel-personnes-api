# referentiel-personnes-api

[![Build Status](https://travis-ci.org/SofteamOuest/referentiel-personnes-api.svg?branch=master)](https://travis-ci.org/SofteamOuest/referentiel-personnes-api)

## Lancement

- Démarrer container docker mongodb. mongo:latest
- Lancer ApplicationStarter

## Base de données

Mongeez gère la montée en version de la base mongodb.
Les données d'initialisation de la base sont dans le fichier V1_1__initial_data.js

Pour ajouter de nouvelles données :

1) créer un fichier V1_X_update_data.js.
2) mettre l'entete :

    // mongeez formatted javascript
    
    // changeset system:v1_1
    
où v1_1 doit être remplacé par la version du script et correspond au préfixe du fichier


