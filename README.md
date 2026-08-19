# Elegance Boutique — Prêt-à-porter

Site vitrine e-commerce statique pour une boutique de prêt-à-porter, avec catalogue produits, panier et commande via WhatsApp.

## Fonctionnalités

- Bannière (vidéo) + hero avec présentation de la marque
- Catalogue produits filtrable par catégorie (femme, homme, accessoires)
- Sélection de taille avec prix variable selon la taille
- Panier latéral (ajout, quantité, suppression, total)
- Commande envoyée directement via WhatsApp (panier + formulaire de contact)
- Section "À propos" et témoignages clients

## Stack

- HTML / CSS / JavaScript vanilla (aucune dépendance externe hormis Google Fonts)
- Images et vidéo stockées dans /images (au lieu d'être encodées en base64)

## Déploiement avec GitHub Pages

1. Aller dans **Settings** → **Pages**
2. Source : branche `main`, dossier `/ (root)`
3. Le site sera disponible à `https://<ton-user>.github.io/<ton-depot>/`

## Personnalisation

- Modifier le tableau `PRODUCTS` dans le `<script>` d'`index.html` pour changer les articles
- Modifier `WHATSAPP_NUMBER` pour rediriger les commandes vers le bon numéro
- Remplacer les fichiers dans /images pour changer les visuels
