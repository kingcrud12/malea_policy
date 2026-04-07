# Malea | Vos commerces tout autour de vous

Malea est une plateforme premium conçue pour redéfinir la découverte locale. Elle permet aux utilisateurs de retrouver tous les commerces et professionnels (restaurants, boutiques, freelances) à proximité avec une expérience fluide et intuitive.

Ce dépôt contient le site marketing principal ainsi que la documentation légale de l'application.

## 🚀 Fonctionnalités Clés

- **Landing Page Premium** : Interface moderne avec carrousel dynamique et design épuré.
- **Portails de Recherche Spécialisés** : 6 univers dédiés (Alimentaire, High-Tech, Mode, Beauté, Professionnels, Restaurants).
- **Intégration Maps en Temps Réel** : Visualisation géographique précise avec la fonction "Rechercher dans cette zone".
- **Centre d'Assistance Avancé** : FAQ multi-niveaux et système de support intégré.
- **Système de Traduction (FR/EN)** : Moteur de traduction ultra-léger en Vanilla JS avec support du LocalStorage.
- **Responsive Design** : Expérience optimisée sur mobile, tablette et desktop.

## 📁 Structure du Projet

```text
.
├── index.html              # Page d'accueil (Landing Page marketing)
├── policy.html             # Politique de Confidentialité
├── malea-cgu.html          # Conditions Générales d'Utilisation
├── translations.js         # Moteur de traduction et dictionnaire partagé
├── malea_map_mockup.png    # Asset visuel (Mockup de l'interface Map)
└── README.md               # Documentation du projet
```

## 🛠️ Stack Technique

- **HTML5** : Structure sémantique et SEO-ready.
- **CSS3** : Design premium (glassmorphism, variables CSS, Flexbox/Grid).
- **Vanilla JavaScript** : Logique de carrousel et système de traduction sans dépendances.
- **Outfit Typography** : Police de caractères premium via Google Fonts.

## 🌍 Système de Traduction

Le projet utilise un système personnalisé via `translations.js` :
- Les éléments sont marqués avec l'attribut `data-i18n`.
- Les titres de page sont gérés dynamiquement via `data-i18n-page-title` sur la balise `<body>`.
- Préférence de langue persistante pour une expérience utilisateur optimale.

## 📄 Licence

&copy; 2026 Malea App. Tous droits réservés.
