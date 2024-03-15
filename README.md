# Projet TRD - Plateforme de Paris Sportifs en Ligne

# SPILMONT François - SAKER Lucas - MATHOUL Olivier

## Installation

1. `composer install`
1. Copiez le fichier `.env.example` en `.env` et modifiez les variables d'environnement
1. `php -S localhost:8000 -t public`

## Lancement DB

1. `docker-compose --env-file .env -f ./trd_docker/docker-compose.yml up -d`
2. `php artisan migrate`
