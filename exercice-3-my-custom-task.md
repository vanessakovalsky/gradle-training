# Exercice 3 - Ajouter mes propres tâches au script


## Définir mes propres tâches
* Ajouter dans notre buld.gradle une tâche qui va afficher un message : 
"Bienvenue dans notre Build"
* Ajouter dans le fichier gradle.properties un propriété "variable" ayant une valeur de votre choix
* Utiliser la propriété variable dans votre tâche pour l'afficher à la suite de votre message
* Définisser dans le build une variable "compteur" qui commence à 0
* A la fin de votre tache, utiliser la méthode doLast pour incrementer la variable "compteur"

## Gérer les dépendances entre tâches

* Créer une seconde tache qui est de type Copy
* Créer un dossier avec le numéro de build depuis la valeur de la variable "compteur"
* Copier les fichiers qui se trouve dans src dans le dossier créé


## Utiliser Gradle Wrapper

* Quelle est la commande à utiliser pour spécifier la version de Gradle à utiliser avec le wrapper ?
* Dans quel fichier se trouve les informations concernant le wrapper ?
* Comment utiliser le wrapper plutôt que l'installation locale de gradle ?