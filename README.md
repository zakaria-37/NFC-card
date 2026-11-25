# Maria Bag — Page réseaux + QR

- `index.html` : page pro avec tous les réseaux (Boutique, Instagram, Facebook, TikTok).
- `cadre.html` : cadre QR 20 × 30 cm prêt à imprimer sur Forex (le QR pointe vers la page d'accueil du site).
- `render.yaml` : configuration Render (site statique).

## Mise en ligne

1. Créer un dépôt GitHub (ex. `maria-bag-links`) et y envoyer ces fichiers.
2. Sur https://dashboard.render.com → **New → Static Site** → choisir le dépôt.
   - Build command : *(vide)* · Publish directory : `.`
3. Ouvrir `https://<votre-site>.onrender.com/cadre.html` → **Imprimer / PDF** → envoyer le PDF à l'imprimeur Forex.

Pour changer un lien : modifier `index.html`, faire un commit → Render redéploie tout seul. Le QR ne change pas.
