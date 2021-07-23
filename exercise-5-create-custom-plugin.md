# Exercice 5 - Création d'un plugin personnalisé

## Création du projet
* Créer un nouveau projet appelé mon-premier-plugin (ou comme vous le souhaitez)
* Celui-ci doit contenir un fichier build.gradle et un dossier src

## Déclaration de l'utilisation de l'API des plugins de gradle et création du fichier
* A l'intérieur du fichier build.gradle, appeler localGroovy (ou autre si vous utilisez Java ou Kotlin pour développer votre plugin) et APIGradle 
* Créer un fichier contenant votre plugin dans le dossier src/votrelangage/com/votredomaine/
* Ecrire la logique de votre plugin en déclarant au moins une tâche

## Publier votre plugin

* Ajouter l'appel à MavenPublish dans le build.gradle avec les informations de publications nécessaires
* Exécuter la tâche MavenPublishLocal de gradle pour publier votre plugin en local

## Utiliser votre plugin

* Ouvrir de nouveau le premier projet
* Appeler le plugin qui a été crée et publié

