# R_ANZAM

Portfolio web de Randria (technicien électronique et technicien systèmes), disponible pour CDD/CDI/mission.

## Démarrage local

```bash
python3 -m http.server 8000
```

Ouvrir ensuite <http://localhost:8000>.

## Déploiement

Le site est déployé automatiquement sur GitHub Pages via `.github/workflows/deploy-pages.yml` lors d'un push sur `main`.

### Mise en ligne (1 seule fois)

1. Aller dans **Settings > Pages** du dépôt GitHub.
2. Dans **Build and deployment**, choisir **Source: GitHub Actions**.
3. Vérifier que la branche par défaut est `main`.
4. Pousser un commit sur `main` pour déclencher le workflow.

Une fois le workflow terminé, l'URL du site est visible dans l'onglet **Actions** (job `Deploy to GitHub Pages`) et dans **Settings > Pages**.
