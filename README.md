# TP: Application Web CRUD avec Spring Boot et Thymeleaf

## Description

Ce TP consiste à développer une application Web CRUD utilisant Spring Boot et Thymeleaf. L'objectif est de comprendre comment créer une application avec une couche DAO qui fournit des fonctionnalités CRUD sur des entités JPA, tout en simplifiant le processus grâce aux outils offerts par Spring Boot.

## Objectifs

- Comprendre l'architecture d'une application Spring Boot utilisant Thymeleaf.
- Implémenter les dépendances Maven nécessaires à la gestion des versions et des plug-ins.
- Configurer l'application pour se connecter à une base de données MySQL.
- Créer une couche de domaine avec des entités JPA.
- Développer une couche de référentiel pour gérer les opérations CRUD.
- Mettre en place une couche contrôleur pour gérer les requêtes HTTP.
- Concevoir la couche présentation avec des templates Thymeleaf.

## Étapes du TP

### 1. Les dépendances Maven

Utiliser `spring-boot-starter-parent` pour une gestion simplifiée des dépendances et des versions.

### 2. Configuration `application.properties`

Configurer la source de données et les propriétés JPA dans le fichier `application.properties`.

### 3. La couche de domaine

Créer les entités qui modélisent les utilisateurs, en utilisant des annotations pour définir les contraintes de validation.

### 4. La couche de référentiel

Étendre l'interface `CrudRepository` pour fournir des opérations CRUD sur les entités.

### 5. La couche contrôleur

Développer les méthodes nécessaires pour gérer les requêtes HTTP, valider les données des formulaires et interagir avec le référentiel.

### 6. La couche présentation

Créer les templates HTML nécessaires pour afficher les formulaires d'inscription, de mise à jour et la liste des utilisateurs.

## Conclusion

Ce TP permet de comprendre comment structurer une application Web CRUD en utilisant Spring Boot et Thymeleaf, en mettant en œuvre les concepts clés de JPA et en facilitant le développement avec les outils fournis par Spring Boot.

## Video de Demonstration  
https://github.com/user-attachments/assets/ca457f3b-7801-4e32-a825-af5677c18475

