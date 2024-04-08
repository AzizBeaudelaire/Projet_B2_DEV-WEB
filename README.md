# Livraison de Repas - Projet Web

Ce projet est un site de livraison de repas développé dans le cadre du cours de Technologies Web et Base de Données. Il permet aux utilisateurs de commander des plats chez différents restaurants, aux restaurateurs de gérer leurs plats et aux administrateurs de gérer le service après-vente.

## Fonctionnalités

- **Partie Membres** :
  - Inscription et connexion des utilisateurs
  - Profil utilisateur avec possibilité de modification
  - Commande de plats avec frais de livraison
  - Envoi d'un email automatique au restaurant après une commande
  - Notation des plats reçus

- **Partie Restaurateurs** :
  - Inscription et connexion des restaurateurs
  - Gestion des plats (ajout, modification, suppression)
  - Profil du restaurant

- **Partie Administrateur** :
  - Authentification des administrateurs
  - Tableau de bord avec statistiques
  - Gestion des restaurants (CRUD)
  - Gestion des clients (CRUD)

## Technologies Utilisées

- Frontend :
  - HTML/CSS
  - React

- Backend :
  - Django

- Base de Données :
  - MySQL

## Installation

1. Clonez ce dépôt sur votre machine locale.
2. Assurez-vous d'avoir installé Node.js, Composer et MySQL sur votre machine.
3. Configurez votre environnement de développement Laravel en suivant les instructions de la documentation officielle : [Laravel Documentation](https://laravel.com/docs/).
4. Créez une base de données MySQL et configurez vos informations de connexion dans le fichier .env.
5. Exécutez les migrations pour créer les tables de base de données en utilisant la commande `php artisan migrate`.
6. Lancez l'application en utilisant la commande `php artisan serve`.

## Contributeurs

- [Votre Nom](lien_vers_votre_profil_github)
- [Nom du Coéquipier](lien_vers_son_profil_github)

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.
