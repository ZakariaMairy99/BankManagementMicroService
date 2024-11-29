# Étape 1 : Build de l'application Angular
FROM node:latest as build

# Définir le répertoire de travail dans le conteneur
WORKDIR /user/local/app

# Copier les fichiers package.json et package-lock.json dans le conteneur
COPY ./ /user/local/app

# Installer les dépendances Angular
RUN npm install

RUN npm run build


# Étape 2 : Servir l'application avec Nginx
FROM nginx:latest

# Copier les fichiers générés dans le répertoire de Nginx
COPY --from=build user/local/app/dist/angular-front-end/browser /usr/share/nginx/html

# Exposer le port 80 pour accéder à l'application
EXPOSE 80
