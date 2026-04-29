# Le Pacific — Restaurant Pizzeria 🍕

Refonte complète du site [le-pacific.fr](https://le-pacific.fr) — Restaurant Pizzeria à Puiseux-en-France.

## Améliorations apportées

### Design
- **Design moderne & professionnel** — Interface épurée avec une typographie soignée (Playfair Display + Inter)
- **Palette de couleurs chaleureuse** — Bleu marine profond 🇫🇷, accents rouges terracotta, doré subtil
- **Responsive mobile-first** — Parfait sur smartphone, tablette et desktop (600px max-width optimisé pour mobile)
- **Hero section immersive** — Image plein écran avec overlay dégradé et boutons d'appel à l'action
- **Effets visuels fluides** — Transitions, ombres portées, animations au scroll, overlay au hover

### UX & Navigation
- **Navigation sticky** — Barre de navigation qui suit le scroll avec effet transparent → solide
- **Navigation par sous-catégories** — Onglets interactifs pour naviguer entre les sections d'une même page
- **Menu mobile** — Panneau latéral coulissant avec animation fluide
- **Back to top** — Bouton de retour en haut flottant
- **Scroll fluide** — Ancres et défilement en douceur

### Structure
- **Page d'accueil complète** — Hero, plats du jour dynamiques, grille de catégories, infos, contact
- **6 pages de catégories** organisées avec sous-catégories :
  - 🍕 Pizzas (Classiques, Spéciales, Suppléments)
  - 🍺 Bières & Softs (Boissons, Eaux, Bières, Boissons Chaudes)
  - 🍷 Vins (Rouges, Blancs, Rosés, Crémants, Pichets)
  - 🍸 Apéro & Cocktails (Apéritifs, Cocktails, Rhums)
  - 🍰 Desserts & Glaces (Maison, Glaces)
  - ☕ Digestifs
- **Footer complet** avec adresse, téléphone, réseaux sociaux

## Structure du projet

```
le-pacific/
├── index.html                  # Page d'accueil
├── styles.css                  # Styles globaux
├── products.css                # Styles pages produits
├── menu_pizzas.html            # Pizzas
├── menu_bieres_softs.html      # Bières & Softs
├── menu_vins.html              # Vins
├── menu_aperitifs_cocktails.html # Apéro & Cocktails
├── menu_desserts.html          # Desserts & Glaces
├── menu_digestifs.html         # Digestifs
└── images/                     # Images du site
    ├── header.jpg
    ├── platsdujour.jpg
    ├── categories/             # Images des catégories
    ├── facebook.jpg
    └── instagram.jpg
```

## Prérequis de déploiement

- Hébergement web standard (PHP pour les plats du jour)
- Les images originales du site doivent être copiées depuis le site actuel
- Le dossier `plats/` avec les scripts PHP existants doit être conservé
- Google Analytics déjà configuré (G-9ZXHEKNM4H)

## Pour le restaurateur

Ce site a été conçu pour :
1. **Attirer plus de clients** via une présence web professionnelle
2. **Faciliter la consultation de la carte** sur mobile
3. **Augmenter les réservations** avec un numéro de téléphone bien visible
4. **Améliorer le référencement** (balises meta, structure sémantique)
5. **Mettre en valeur les plats du jour** et les produits frais
