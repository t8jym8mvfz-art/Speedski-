# Speedski Gestion

Application de devis, bons de commande, factures, achats de véhicules et factures de réparation pour **VV Passion Speedski** (Staffelfelden). Elle crée les PDF aux couleurs de la carte de visite.

## Mettre en ligne avec GitHub Pages

1. Sur github.com, créer un nouveau dépôt **public**, par exemple `speedski`.
2. Dans le dépôt : **Add file → Upload files**, puis déposer les 6 fichiers de ce dossier (`index.html`, `sw.js`, `manifest.json`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`). Valider avec **Commit changes**.
3. **Settings → Pages** : dans *Build and deployment*, choisir **Deploy from a branch**, branche **main**, dossier **/ (root)**, puis **Save**.
4. Après une à deux minutes, l'app est disponible à l'adresse `https://NOM-DU-COMPTE.github.io/speedski/`.

## Installer sur le téléphone

- **iPhone** : ouvrir l'adresse dans Safari, bouton Partager, puis « Sur l'écran d'accueil ».
- **Android** : ouvrir l'adresse dans Chrome, menu ⋮, puis « Installer l'application ».

Une fois ouverte une première fois, l'app fonctionne sans internet.

## Où sont les données ?

Les documents et les clients sont enregistrés **sur le téléphone**, jamais sur GitHub. Pensez à exporter une sauvegarde de temps en temps (Réglages → Sauvegarde) et à la garder dans iCloud Drive ou Google Drive. Elle se réimporte avec le bouton Importer.

## Mettre à jour

Remplacer `index.html` dans le dépôt (Add file → Upload files). Le téléphone reçoit la nouvelle version à la prochaine ouverture avec internet ; les documents enregistrés sont conservés.
