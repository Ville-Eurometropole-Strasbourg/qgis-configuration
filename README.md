# Qgis Configuration

Ce dépôt contient les configuration nécessaire pour la Qgis Deployment toolbelt.

la QDT est un outil permettant de déployer des configuration Qgis de manière centralisé.

Docummentation de la QDT :

https://qgis-deployment.github.io/qgis-deployment-toolbelt-cli/

## Détails des profils 

### Main

Profil principal déployé pour les utilisateurs classique de Qgis dans les services. Il comprend une configuration d'interface minimale et les plugins basique apckagés avec Qgis depuis le lancement de SIGLI.

### GCT

Profil destiné au service GCt, comprend davanatge d'élements de configuration, une itnerface plus avancé, ainsi que l'ajout de liens vers un fichier de configuration de Postgres en mode service pour la gestion de Qgis Web.

### Eau et Assainissement

Profil destiné au service Eau et Assainissement, il permet d'inclure les plugins métiers utile au service ainsi que un lancement par défaut sur le projet maitre "TopEau". 