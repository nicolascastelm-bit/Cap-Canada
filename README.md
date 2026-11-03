# Cap Canada V2 — Journalisme sportif

Site statique utilisable directement en ouvrant `index.html`, ou en publiant le fichier sur GitHub Pages.

## Fonctions
- Annuaire de 47 médias, recherche et filtres.
- Espace personnel local (nom, e-mail, sélection des PDF et message-type).
- Éditeur de lettres de motivation personnalisées par rédaction, en français ou en anglais.
- Enregistrement des brouillons, export TXT ou impression PDF.
- Validation explicite par candidature avant ouverture de la messagerie ou du portail de l'employeur.
- Confirmation **manuelle après envoi réel**, historique de statut, dates, notes et relances.
- Sauvegarde JSON et export CSV.

## Limites importantes
Aucun envoi automatique : `mailto:` ouvre le logiciel de messagerie installé, sans pièce jointe. L'utilisateur joint son CV et sa lettre, puis envoie lui-même. Les formulaires employeurs doivent être remplis sur leurs sites. Le site ne vérifie pas l'existence des adresses de contact. Il n'y a pas d'authentification serveur, ni de synchronisation : les données restent dans le navigateur (`localStorage`), et les fichiers PDF sélectionnés ne sont pas stockés. Ne pas utiliser un appareil partagé. Les liens d'emploi et la disponibilité des offres doivent être vérifiés.

## Installation GitHub Pages
Créer un dépôt GitHub, envoyer `index.html`, puis activer Settings > Pages > Deploy from a branch > main / root. Aucun Firebase requis pour cette version.
