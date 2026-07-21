# Fleur Cognac — page de redirection

Site statique (dossier `public/`) prêt pour Vercel.

## Déployer

Option A — Vercel CLI :
```
npm i -g vercel
cd fleur-cognac-redirect
vercel --prod
```

Option B — Dashboard Vercel :
1. Créer un nouveau projet, importer ce dossier (ou le pousser sur un repo Git).
2. Framework preset : "Other".
3. Output directory : `public`.
4. Déployer.

## Fichiers

- `public/index.html` — la page (logo, titre, bouton vers Fine Spirits, bulle Contactez-nous)
- `public/fond.jpg` — image de fond
- `public/logo.jpg` — logo Fleur Cognac XO

## À personnaliser

- Le lien du bouton pointe vers `https://www.fine-spirits.com` — à ajuster si l'URL exacte diffère.
- La bulle "Contactez-nous" est décorative pour l'instant (pas de lien).
