# DEPLOIEMENT — Mise en production

Ce dossier contient tous les scripts qui permettent de **mettre le site en ligne** et de gérer les environnements de déploiement.

## Rôle
- Automatiser la mise en production du site.
- Gérer les différents environnements (développement, test, production).
- Configurer les serveurs et les services (base de données, API, frontend).

## Contenu attendu
- **`deploy.sh`** : Script principal de déploiement.
- **`config/`** : Fichiers de configuration des environnements (ex: `production.yml`, `staging.yml`).
- **`docker/`** : Fichiers Docker si le projet est conteneurisé (`Dockerfile`, `docker-compose.yml`).

## ⚠️ Règles de sécurité
- **Ne jamais commiter de secrets** (mots de passe, clés SSH, tokens) dans ce dossier. Utilisez des variables d'environnement.
- **Toujours tester** un script de déploiement en local ou sur un environnement de test avant de le lancer en production.
- **Documenter chaque script** : indiquer son rôle, ses paramètres et ses prérequis.
