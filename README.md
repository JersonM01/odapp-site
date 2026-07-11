# Site web ODAPP

Site vitrine de l'ODAPP (Organisation de Développement Agro-Pastoral et Piscicole), Sud-Kivu, RDC.

## Structure
- `index.html` — Accueil
- `a-propos.html` — Vision, mission, historique
- `projets.html` — Liste des projets
- `contact.html` — Formulaire de contact (Formspree)
- `projets/` — Pages détaillées de chaque projet
- `css/`, `js/`, `assets/` — Styles, scripts, images/logo/PDF

## Déploiement
Ce site est 100% statique (HTML/CSS/JS, aucun build nécessaire).
Déployé sur Netlify, connecté à ce dépôt GitHub pour un déploiement automatique à chaque push sur `main`.

## Développement local
Ouvrir simplement `index.html` dans un navigateur, ou lancer un serveur local :
```
python3 -m http.server 8000
```
