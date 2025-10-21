# Étape 1 : Choisir l'image de base Apache
FROM httpd:2.4

# Étape 2 : Copier la page d'accueil dans le dossier web par défaut d'Apache
COPY index.html /usr/local/apache2/htdocs/

# Étape 3 : Copier la configuration personnalisée 
COPY httpd.conf /usr/local/apache2/conf/httpd.conf
