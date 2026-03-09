# ALONE - Site Web ONG Caritative

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Description du Projet

**ALONE** est un site web institutionnel pour une organisation non gouvernementale (ONG) dédiée à l'aide humanitarian internationale. Ce projet a été développé lors d'un **test technique** pour un poste de **stagiaire développeur web**.

Le site présente les différentes actions de l'ONG, ses causes, ses événements, une boutique de produits et les dernières nouvelles.

## Fonctionnalités

### Pages/Sections
- **Header** : Navigation responsive avec menus déroulants
- **Hero Section** : Section d'accueil avec appel à l'action
- **À propos** : Présentation de la mission de l'ONG
- **Causes** : Liste des projets caritatifs avec objectifs de dons
- **Événements** : Calendrier des événements à venir
- **Boutique** : Produits thématiques (commerce éthique)
- **Témoignages** : Avis clients
- **Actualités** : Dernières nouvelles et articles
- **Newsletter** : Formulaire d'inscription
- **Footer** : Coordonnées, liens rapides et réseaux sociaux

### Caractéristiques Techniques
- ✅ Site mono-page (Single Page Application)
- ✅ Design responsive (Mobile, Tablette, Desktop)
- ✅ Chargement dynamique du contenu via JavaScript
- ✅ Animations et effets au survol
- ✅ Icônes Font Awesome
- ✅ Polices Google Fonts

## Structure du Projet

```
app/
├── index.html          # Structure HTML principale
├── style.css           # Styles CSS (avec media queries)
├── script.js           # Logique JavaScript (données dynamiques)
├── README.md           # Ce fichier
├── libs/               # Images et ressources
│   ├── *.jpg, *.png, *.webp, *.svg
└── maquettes/          # Documents de référence
    ├── Version PDF pour selection de text.pdf
    └── Version PGN.png
```

## Technologies Utilisées

| Technologie | Description |
|-------------|-------------|
| **HTML5** | Structure sémantique du site |
| **CSS3** | Styling, flexbox, grid, animations, responsive |
| **JavaScript** | Manipulation du DOM, données dynamiques |
| **Font Awesome** | Bibliothèque d'icônes |
| **Google Fonts** | Typographie (Funnel Sans, Mea Culpa) |

## Installation

1. Clonez ce dépôt ou téléchargez les fichiers
2. Ouvrez le fichier `index.html` dans votre navigateur

```bash
# OU utiliser un serveur local
npx serve .
```

## Détails Techniques

### Responsive Breakpoints
- **Desktop** : > 768px
- **Tablette** : 480px - 768px
- **Mobile** : < 480px

### Données Dynamiques
Le contenu est généré via JavaScript à partir de tableaux d'objets :
- `data` : Objectifs de développement durable (ODD)
- `icone` : Statistiques de l'ONG
- `articles` : Causes caritatives
- `produits` : Articles de la boutique
- `news` : Actualités

## Captures d'Écran

Le site comprend :
- Une bannière héro avec image de fond
- Des cartes interactives pour les ODD
- Une section vidéo institutionnelle
- Une galerie de causes avec progressifs de dons
- Une boutique e-commerce
- Un formulaire de newsletter
- Un pied de page complet

## Auteurs

- **Développeur** : Ahmed Combo Rachad
- **Projet** : Test technique - Stage Développeur Web
- **Entreprise** : Polaris Asso

## Licence

Ce projet est un travail académique/test - Tous droits réservés.

---

*Développé lors d'un test technique pour Polaris Asso*

