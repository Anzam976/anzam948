# R_ANZAM — Portfolio de Randria

Portfolio web statique en français pour présenter **Randria**, technicien électronique et technicien systèmes, en recherche d'opportunités (**CDD, CDI, mission**).

## Lancer en local

```bash
python3 -m http.server 8000
```

Puis ouvrir : <http://localhost:8000>

## Mettre le site en ligne (GitHub Pages)

Le dépôt inclut un workflow GitHub Actions (`.github/workflows/deploy-pages.yml`) qui publie automatiquement le site sur **GitHub Pages** à chaque push sur `main`.

### Étapes

1. Pousser ce dépôt sur GitHub.
2. Aller dans **Settings > Pages**.
3. Dans **Build and deployment**, choisir **GitHub Actions** comme source.
4. Faire un push sur `main` (ou relancer le workflow) puis attendre la fin du job **Deploy static content to Pages**.
5. L'URL publique sera fournie dans la section Pages du dépôt.
