# Sylvaë Sophrologie — site one-page

Site statique prêt pour GitHub Pages.

## Contenu
- `index.html` — la page
- `support.js` — moteur d'affichage (ne pas modifier)
- `brand/` — logo arbre et logo de la Maison de santé de Pouzolles
- `sylvie-verdier-portrait.jpg` — photo « Qui suis-je ? »
- `robots.txt`, `sitemap.xml` — référencement
- `.nojekyll` — indique à GitHub Pages de servir les fichiers tels quels

## Mise en ligne
1. Créer un dépôt GitHub (ex. `sylvae-sophrologie`).
2. Déposer **tout le contenu de ce dossier** à la racine du dépôt (index.html doit être à la racine).
3. Settings → Pages → Source : *Deploy from a branch* → branche `main`, dossier `/ (root)` → Save.
4. Le site est en ligne après 1–2 minutes à l'adresse `https://VOTRE-COMPTE.github.io/sylvae-sophrologie/`.

## Nom de domaine (recommandé)
1. Settings → Pages → Custom domain : saisir le domaine (ex. `sylvae-sophrologie.fr`), cocher *Enforce HTTPS*.
2. Chez le registraire du domaine, créer 4 enregistrements A vers 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153, et un CNAME `www` vers `VOTRE-COMPTE.github.io`.

## À compléter avant la mise en ligne
- **Formulaire de contact** : dans `index.html`, chercher `VOTRE_PUBLIC_KEY` et remplacer les trois identifiants EmailJS. Dans EmailJS, ajouter le domaine du site aux domaines autorisés.
- **robots.txt / sitemap.xml** : remplacer `VOTRE-DOMAINE` par l'adresse définitive.
- **index.html** : compléter `<link rel="canonical" href="/">` et `og:image` avec l'adresse complète (https://…).
- **Mentions légales** (dans `index.html`, chercher `[À compléter`) : hébergeur, assurance RC pro, médiateur de la consommation. Pour GitHub Pages, l'hébergeur est : GitHub Inc., 88 Colin P. Kelly Jr. Street, San Francisco, CA 94107, États-Unis.

## Après la mise en ligne
- Déclarer le site dans Google Search Console et y envoyer `sitemap.xml`.
- Ajouter l'adresse du site à la fiche Google Business Profile.
