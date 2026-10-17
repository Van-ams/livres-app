# Application de Recherche de Livres

Projet Java EE (Servlets + JSP) avec base de données MySQL.

## Prérequis
- JDK 8
- Maven
- Tomcat 9
- XAMPP (MySQL)

## Installation
1. Démarrer XAMPP (Apache + MySQL).
2. Créer une base de données nommée `livres_db` dans phpMyAdmin.
3. Importer le fichier `livres_db.sql` fourni.
4. Dans un terminal, à la racine du projet : `mvn clean package`
5. Copier `target/livres-app.war` dans le dossier `webapps` de Tomcat.
6. Démarrer Tomcat.
7. Ouvrir : `http://localhost:8080/livres-app/` (ou `https://localhost:8443/livres-app/` si HTTPS configuré).

## Fonctionnalités
- Recherche locale (MySQL) et externe (Open Library / Google Books)
- Espace administrateur (login sécurisé) avec CRUD complet
- Upload d'images et de fichiers PDF
- Gestion des commandes
