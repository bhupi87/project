# Project Management


## Outils de developpement

* Java 8
* Gradle
* Spring boot 1.5.3.RELEASE
* H2 database
* Sring data jpa
* Spring MVC
* Thymeleaf
* Spring security

## Installation

* Télécharger ou cloner le code source depuis git repository
```
git clone http://github.com/salah3x/project-manager
```
* Naviguer vers le dossier téléchargé
```

cd [Path to project-manager]
```
* Démarer l'application :
```
./gradlew bootRun
```
ou éxécuter directement le jar
```
./gradlew bootRepackage
java -jar build/libs/project-manager-0.0.1-SNAPSHOT.jar
```
* Allez à http://localhost:8080/

**Remarque 1:**
La commande ./gradlew necessite une connexion internet et peut pendre du temps pour télécharger les dépendeces de l'application.

**Remarque 2:**
Pour démarer l'application sous windows utiliser le fichier gradlew.bat au lieu du gradlew.

# project
