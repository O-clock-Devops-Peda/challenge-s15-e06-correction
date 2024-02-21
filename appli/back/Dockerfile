# Utiliser une image de base Python
FROM python:3.9

# Définir le répertoire de travail dans le container
WORKDIR /app

# Copier le fichier d'application dans le répertoire de travail
COPY app.py /app

# Installer les dépendances
RUN pip install flask

# Exposer le port sur lequel l'application Flask s'exécute
EXPOSE 5000

# Commande pour exécuter l'application lorsque le container démarre
CMD ["flask", "run", "--host=0.0.0.0"]
