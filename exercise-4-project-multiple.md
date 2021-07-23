# Exercice 4 - Structurer un projet multi-projet

## Création d'une structure multi-projet
* Ajouter dans votre projet un sous projet (dossier du sous projet contenant lui même un dossier src avec les sources + un fichier de build.gradle)
* Dans votre fichier settings.gradle ajouter l'appel à ce nouveau sous-projet
* En utilisant la commande gradle tasks vous devriez voir également les tâches du sous-projet 

## Ajouter des tests à son build

* Ajouter des tests unitaires à votre projet
* Lancer la tâche Test par défaut de Gradle, et observer ce qu'il se passe 
* Ajouter une étape dans le build.gradle qui appellera ces tests en spécifiant le dossier contenant les tests ou seulement une partie des tests 
* Lancer votre nouvelle tâche

## Publier son projet

* Ajouter une étape de publication avec MavenPublish a votre build.gradle
* Lancer la tache MavenPublishLocal de gradle pour publier votre application sur votre depôt Maven Local