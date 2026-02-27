# ERP-INFRA
C'est le repo qui va permettre d'orchestrer le SQL Server et les microservices

Ce que vous êtes concernée de faire est de cloner ce repo et le repo de votre microservice dans le même workspace, et tu créer dans chaque projet un fichier .env qui doit contenir ce ligne de code (DB_PASSWORD=[faire entrée un mdp d'au moins 8 caractères, majuscule, minuscule, chiffre,caractère spécial]), puis tu accède au projet de l'infra et tu exécute cette commande dans le terminal: 
       - docker compose up --build [nom du microservice qui se trouve dans le fichier docker-compose.yml) 
        Par exemple: docker compose up --build gestionprojet-api.(Il faut installer Docker Desktop avant de générer cette commande.)


