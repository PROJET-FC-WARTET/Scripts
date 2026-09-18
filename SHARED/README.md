# SHARED — Code réutilisable pour les scripts

Ce dossier contient les fonctions, classes ou constantes **utilisées par plusieurs scripts** du dépôt.

## Rôle
- Éviter la duplication de code entre les scripts.
- Centraliser les utilitaires communs (logs, gestion des erreurs, connexion SSH, etc.).
- Faciliter la maintenance (un seul endroit à modifier).

## Exemples de contenu
- **`logger.sh`** : Fonction de journalisation des opérations.
- **`utils.sh`** : Fonctions utilitaires (vérification de fichiers, formatage).
- **`config.sh`** : Chargement des variables d'environnement.

## Règle
> Si une fonction est utilisée dans **plus d'un script**, elle doit être placée ici.
