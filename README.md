# Radar Emploi Mâcon

Suivi des offres vente & commerce à Mâcon et alentours (Charnay-lès-Mâcon, Prissé, Sancé, Crêches-sur-Saône), accessibles sans voiture — à pied ou en bus Tréma.

**Site en ligne :** https://julesvalet.github.io/radar-emploi-macon/

## Fonctionnalités

- Liste des offres avec filtres (toutes, nouvelles, Mâcon)
- Pour chaque offre : prompt CV, lettre de motivation prête à coller, prompt IA pour une lettre sur-mesure
- « Postulé » : suivi des candidatures avec téléphone et notes
- « Pas intéressé » : masque une offre

Le suivi et les offres masquées sont enregistrés dans le navigateur (localStorage) : ils restent propres à chaque appareil.

## Mettre à jour les offres

Les offres sont dans l'objet `DATA` en haut du `<script>` de [`index.html`](index.html). Remplace le fichier puis fais un commit : GitHub Pages republie le site automatiquement.
