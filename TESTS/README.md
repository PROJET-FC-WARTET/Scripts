# TESTS — Validation des scripts

Ce dossier contient les **tests** qui vérifient que les scripts fonctionnent correctement avant d'être utilisés en production.

## Rôle
- S'assurer qu'un script de déploiement ne casse rien.
- Tester les scripts dans un environnement isolé.
- Vérifier que les scripts se comportent correctement en cas d'erreur.

## Contenu attendu
- **`test_deploy.sh`** : Tests du script de déploiement.
- **`test_utils.sh`** : Tests des fonctions utilitaires.
- **`fixtures/`** : Fichiers de test (données fictives, configurations de test).

## Règles
- **Un test doit pouvoir être exécuté** sans affecter la production.
- **Chaque nouveau script** doit être accompagné d'au moins un test de base.
- Les tests doivent être **automatisables** (pas d'intervention manuelle).
