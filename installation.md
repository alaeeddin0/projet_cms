### les identifiants : 
login :     admin
mdp   :  admin123

login  :   contributeur
mdp    : contributeur123

login  :   editeur
mdp   :  editeur123

# Projet WordPress - Site E-Commerce  

Ce projet est un site e-commerce construit avec WordPress et WooCommerce, conçu pour vendre des produits high-tech.  

## **Prérequis**  
Avant de commencer, assurez-vous d’avoir :  
1. Un serveur local installé (XAMPP, WAMP, MAMP, ou équivalent).  
2. Une version récente de PHP (>= 7.4) et MySQL.  
3. WordPress téléchargé et installé.  

---

## **Instructions d’installation**  

### **Étape 1 : Téléchargement des fichiers**  
1. Clonez le projet depuis GitHub :  
   ```bash
   git clone https://github.com/alaeeddin0/projet_cms.git
   
### Étape 2 : Configuration de la base de données
Lancez votre serveur local et ouvrez phpMyAdmin en accédant à :
http://localhost/phpmyadmin
Créez une nouvelle base de données nommée wordpress
### Étape 3 : Configurer WordPress
Accédez au fichier wp-config.php dans le dossier du projet.
Modifiez les paramètres de connexion à la base de données :
php

define('DB_NAME', 'wordpress'); // Nom de la base de données
define('DB_USER', 'root');                // Nom d'utilisateur (par défaut : root)
define('DB_PASSWORD', '');               // Mot de passe (vide pour XAMPP)
define('DB_HOST', 'localhost');          // Hôte (localhost pour serveur local)
### Étape 4 : importer la base de données WordPress
le fichier est existant dans github
