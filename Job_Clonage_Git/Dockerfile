# Utiliser une image Python officielle
FROM python:3.11-slim

# Dfinir le rpertoire de travail dans le conteneur
WORKDIR /app

# Copier les fichiers locaux dans le conteneur
COPY . .

# Installer les dpendances
RUN pip install -r requirements.txt

# Excuter les tests avec pytest
CMD ["pytest", "tests/"]

