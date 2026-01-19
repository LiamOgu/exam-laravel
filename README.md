# Évaluation Laravel - Authentification avec Breeze

## Description

Projet d'évaluation Laravel avec système d'authentification en utilisant Breeze.

## Installation

```bash
cd evaluation
composer install
php artisan migrate
php artisan serve
```

## Base de données

Table `users` :

- id (primary key)
- nom
- prenom
- email (unique)
- password (hashé avec bcrypt)
- timestamps

## Git

- Branche `main` : version stable
- Branche `develop` : développement

## Accès

- Page d'accueil : http://localhost:8000
- Inscription : http://localhost:8000/register
- Connexion : http://localhost:8000/login
- Dashboard : http://localhost:8000/dashboard
