# Utiliser l'image nginx
FROM nginx:latest

# Supprimer le fichier par défaut index.html de nginx
RUN rm -rf /usr/share/nginx/html/*

# Copier votre fichier index.html dans le répertoire de base de nginx
COPY index.html /usr/share/nginx/html

# Exposer le port sur lequel nginx écoute
EXPOSE 80

# Commande pour démarrer nginx lors du démarrage du container
CMD ["nginx", "-g", "daemon off;"]
