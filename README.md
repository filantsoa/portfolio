## Portfolio Monja Filantsoa

Site statique moderne construit en HTML/CSS pur pour présenter le profil de Monja Filantsoa (développeur full stack).

### Aperçu local

```bash
npx serve .
# ou
python3 -m http.server 4173
```

### Déploiement GitHub Pages

1. Crée un dépôt GitHub (ex: `portfolio-monja`).
2. Ajoute l’origine distante et pousse le code :
   ```bash
   git remote add origin git@github.com:<ton-user>/portfolio-monja.git
   git push -u origin main
   ```
3. Dans GitHub → `Settings` → `Pages` :
   - Section “Build and deployment” → `Source: Deploy from a branch`
   - `Branch: main` et dossier `/ (root)` puis `Save`.
4. GitHub génère automatiquement l’URL : `https://<ton-user>.github.io/portfolio-monja/`.

> Remplace `<ton-user>` par ton pseudo GitHub réel. L’URL sera disponible après quelques minutes (pense à vider le cache si besoin).
