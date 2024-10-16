# Utiliser l'image PHP-FPM comme base
FROM php:8.1-fpm

# Définir le répertoire de travail
WORKDIR /app

# Copier le fichier index.php dans le répertoire de travail
COPY index.php .

# Donner les permissions à www-data
RUN chown -R www-data:www-data /app
