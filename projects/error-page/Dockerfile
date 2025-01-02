# Étape 1: Utiliser une image de base officielle Nginx
FROM nginx:alpine

# Étape 2: Copier le fichier HTML dans le répertoire de Nginx
COPY index.html /usr/share/nginx/html/

# Étape 3: Exposer le port 80 pour accéder à la page via HTTP
EXPOSE 80

# Étape 4: Démarrer Nginx pour servir la page
CMD ["nginx", "-g", "daemon off;"]