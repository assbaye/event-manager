# Event Manager

Application de gestion d'événements avec:
- Backend: Laravel 12
- Frontend: Angular 

## Structure du projet
- `/backend` : API Laravel
- `/frontend` : Application Angular

## Installation

### Backend
```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serves