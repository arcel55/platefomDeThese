# platefomDeThese

# Installation

```bash
git clone https://github.com/arcel55/platefomDeThese

cd platefomDeThese

composer install

npm install
```

# Configuration du .env

```bash
cp .env.example .env
```

# Configuration de la base de données

```bash
edit .env

DB_CONNECTION=mysql
DB_HOST=your-host
DB_PORT=3306
DB_DATABASE=your-database
DB_USERNAME=your-username
DB_PASSWORD=your-password
```

# Génération de la clé d'application et migration de la base de données
```bas
php artisan key:generate

php artisan migrate

php artisan db:seed
```
