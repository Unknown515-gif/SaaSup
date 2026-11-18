# SaaSup.ai

Site statique : landing page + onboarding (questionnaire, calcul, résultats) dans une seule page.

## Fichiers
- `index.html` : la page (landing + onboarding)
- `styles.css` : tout le design
- `app.js` : la logique de l'onboarding (questions, curseur, calcul, résultats)

## Mettre sur GitHub
1. Crée un dépôt vide sur github.com (New repository).
2. Clique sur **Add file → Upload files**, glisse les 4 fichiers (`index.html`, `styles.css`, `app.js`, `README.md`), puis **Commit changes**.

## Mettre en ligne sur Vercel
1. Sur vercel.com : **Add New → Project**, importe ton dépôt GitHub.
2. Framework Preset : **Other**. Ne mets aucune commande de build. Clique sur **Deploy**.

## Pas encore fait
- Le formulaire email n'enregistre rien (Supabase vient après GitHub et Vercel).
- Boutons « Log in », Google et liens Terms / Privacy / Refunds : pas encore reliés.
- Les notifications Stripe du téléphone sont une illustration, pas de vraies ventes.
