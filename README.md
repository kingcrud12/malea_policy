# Malea Policy & Terms of Use

This repository contains the legal documentation for the **Malea** application, including the Privacy Policy and the General Terms of Use (CGU). 

The site is designed with a premium aesthetic and features a custom multi-language system (French and English).

## 🚀 Features

- **Multi-language Support**: Seamless switching between French and English using a custom lightweight JavaScript translation engine.
- **Responsive Design**: Optimized for all devices using modern CSS and the "Outfit" typography.
- **Premium UI**: Clean, card-based layout with subtle animations and glassmorphism-inspired elements.
- **Persistent Preferences**: User language selection is saved in `localStorage`.

## 📁 Project Structure

```text
.
├── index.html          # Privacy Policy (Politique de Confidentialité)
├── malea-cgu.html      # Terms of Use (Conditions Générales d'Utilisation)
├── translations.js     # Shared translation logic and dictionary (FR/EN)
└── README.md           # Project documentation
```

## 🛠️ Technology Stack

- **HTML5**: Semantic structure.
- **CSS3**: Custom styling with variables and flexbox/grid.
- **Vanilla JavaScript**: Lightweight translation handling and UI interactions.
- **Google Fonts**: "Outfit" font family.

## 🌍 Translation System

The project uses a custom `translations.js` file that contains all strings for the site. 
- Elements are marked for translation using the `data-i18n` attribute.
- Page titles are updated via the `data-i18n-page-title` attribute on the `<body>` tag.
- Language preference is automatically detected from the browser or retrieved from local storage.

### Adding a new language
To add a new language, simply update the `translations` object in `translations.js` with the new key (e.g., `es` for Spanish) and add a button to the language switcher in the HTML files.

## 📄 License

&copy; 2026 Malea App. All rights reserved.
