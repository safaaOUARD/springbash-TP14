# Automatisation du cycle de vie d'une application Spring Boot avec Bash

TP réalisé dans le cadre du cycle ingénieur ISIC (ENSA El Jadida) : automatiser le déploiement, l'exécution et la surveillance d'une application Spring Boot avec des scripts Bash.

## Objectif
Remplacer les manipulations manuelles par des scripts réutilisables, comme dans une démarche DevOps.

## Scripts (dossier `scripts/`)
- `deploy.sh` : construit et déploie l'application.
- `run.sh` / `stop.sh` : démarre et arrête l'application.
- `healthcheck.sh` : vérifie que l'application répond.
- `logs.sh` : consulte les journaux de l'application.
- `archive-logs.sh` : archive les journaux (fichiers `.tar.gz` datés).

## Technologies
Bash · Linux · Java · Spring Boot · Maven

## Utilisation
```bash
chmod +x scripts/*.sh
./scripts/deploy.sh
./scripts/healthcheck.sh
```

## Ce que j'ai appris
Écrire des scripts Bash pour automatiser le déploiement, vérifier l'état d'un service et gérer ses journaux.
