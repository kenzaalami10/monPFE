# Application Flask avec Docker

Cette application est une simple application Flask avec une API de base qui retourne un message de bienvenue.

## Utilisation

Pour exécuter localement l'application Flask, assurez-vous d'avoir Python installé sur votre machine. Vous pouvez exécuter l'application en suivant ces étapes :

1. Installez les dépendances en exécutant la commande suivante dans votre terminal :
pip install -r requirements.txt


2. Lancez l'application en exécutant la commande suivante dans votre terminal :
python src/app.py


L'application sera alors disponible à l'adresse http://localhost:5000.

## Docker

Cette application peut également être exécutée dans un conteneur Docker. Assurez-vous d'avoir Docker installé sur votre machine. Vous pouvez construire et exécuter l'image Docker en suivant ces étapes :

1. Construisez l'image Docker en exécutant la commande suivante dans votre terminal, à partir du répertoire racine de votre projet :
docker build -t basic-flask-app .



L'application Flask sera alors accessible à l'adresse http://localhost:5000 depuis votre navigateur.

## API

Cette application expose une seule route :
- GET / : Retourne un message de bienvenue.


