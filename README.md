# Maria Bag — Carte NFC — Boudjellal Boualem (CEO)

Page ouverte quand on approche un téléphone de la carte NFC de Boudjellal Boualem.

- `index.html` : page du gérant (Appeler, WhatsApp 0550 57 50 93, Enregistrer le contact, boutique et réseaux).
- `carte.html` : conception de la carte NFC recto / verso (85,6 × 54 mm + fond perdu) avec QR personnalisé.
- `contact.vcf` : fiche contact téléchargée par le bouton « Enregistrer ».
- `intro.mp4`, `logo.png` : vidéo d'intro et logo.

En ligne : https://nfc-card-qisa.onrender.com (Render, Static Site, redéploiement automatique à chaque commit sur `main`).

## Programmer la carte NFC

1. Installer l'appli **NFC Tools** (Android / iPhone).
2. **Écrire → Ajouter un enregistrement → URL** : `https://nfc-card-qisa.onrender.com`
3. **Écrire**, puis approcher la carte du téléphone.
4. (Optionnel) **Autres → Verrouiller la puce** pour qu'elle ne puisse plus être modifiée — irréversible.

Pour changer le numéro : modifier `+213550575093` dans `index.html` et `contact.vcf`.
