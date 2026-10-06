# Sgariboldi — Formulaire Sommet de l'Élevage 2026

Site statique, un seul fichier (`index.html`, autonome, fonctionne hors ligne une fois chargé).

## Publication (GitHub → Netlify)
1. Créer un dépôt GitHub et y pousser le contenu de ce dossier (`index.html`, `netlify.toml`, `README.md`).
2. Netlify → *Add new site* → *Import from Git* → choisir le dépôt.
3. Build command : vide · Publish directory : `.` → *Deploy*.

## Envoi des fiches
Chaque fiche est envoyée à Netlify Forms (formulaire « sommet-elevage-2026 », déclaré dans `__forms.html`).
Les fiches sont visibles dans Netlify → *Forms*, et une notification e-mail est envoyée à :
- alessandro.donati@sgariboldi.it
- france@sgariboldi.it
- federica.barbarotto@sgariboldi.it

Les destinataires se gèrent dans Netlify → *Project configuration > Notifications > Emails and webhooks > Form submission notifications*.

## Sur le salon
- Sans réseau : les fiches sont stockées sur la tablette et renvoyées automatiquement au retour de la connexion (bouton « Renvoyer en attente » en bas de page).
- « Exporter CSV » télécharge toutes les fiches saisies sur l'appareil (sauvegarde, import CRM).
- Utiliser la même tablette / le même navigateur pendant tout le salon ; ne pas vider les données du navigateur avant l'export.
