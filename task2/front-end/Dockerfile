# Utiliser l'image officielle de Nginx
FROM nginx:latest

# Copier les fichiers front-end dans le répertoire web de Nginx
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copier le fichier de configuration personnalisé de Nginx
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

EXPOSE 9000
