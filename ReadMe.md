# OhMyFood 🍽️

Projet réalisé dans le cadre de la formation OpenClassrooms - Développeur Web.

> Intégration complète d'un site web de réservation de menus gastronomiques pour plusieurs restaurants parisiens.

---

## 🎯 Objectifs pédagogiques

- Concevoir une **interface responsive** avec une approche **Mobile First**.
- Réaliser des **animations dynamiques** et des **effets d’interaction uniquement avec du HTML et du SCSS** (aucune ligne de JavaScript).
- Structurer un projet de manière modulaire avec **un système de composants SCSS réutilisables**.
- Mettre en ligne le projet sur **GitHub Pages** pour en assurer l’accessibilité publique.

---

## 🧰 Technologies utilisées

- **HTML5** : structure sémantique claire et accessible
- **Sass (SCSS)** : organisation des styles, variables, mixins, animations
- **CSS3** : effets visuels, flexbox, media queries
- **Git & GitHub** : versioning du code et hébergement en ligne

---

## 💡 Particularités du projet

- 💅 **Animations avancées** : toutes les animations (loader, apparitions, interactions, effets de survol) sont réalisées **exclusivement en CSS / SCSS**, sans JavaScript.
- 📱 **Responsive Mobile First** : la maquette a été intégrée en suivant une approche mobile first, avec des media queries adaptatives pour tablettes et desktops.
- ♻️ **SCSS modulaire** : fichiers organisés par variables, composants, animations et pages, facilitant la lisibilité et la maintenance.

---

## 🚀 Installation et Setup local

1. **Cloner le projet** :
   ```bash
   git clone https://github.com/delia-1/p-3-oh-my-food-.git
   cd p-3-oh-my-food-

### 2. Lancer en local

Ce projet est **statique** (HTML + SCSS uniquement), il peut donc être ouvert directement dans votre navigateur :

- ✅ En ouvrant le fichier `index.html` manuellement dans votre navigateur
- ✅ Ou via une extension comme **Live Server** dans VS Code

---

### 3. Compiler les fichiers SCSS

Le projet utilise **Sass (SCSS)**.
Aucune dépendance JavaScript n'est nécessaire, mais vous pouvez compiler les fichiers SCSS avec Sass en local si vous souhaitez modifier les styles.

#### ▶️ Installer Sass CLI (si besoin)

<!-- ```bash
npm install -g sass -->
#### Compiler automatiquement
<!-- sass ./scss:./css --watch -->

# 💅 Particularités techniques

### 🔁 100% HTML + SCSS

Ce projet a été volontairement réalisé **sans JavaScript**.
Toutes les interactions, effets et animations sont conçues **exclusivement avec SCSS/CSS**, y compris :

- Le loader d’introduction
- Les animations d’apparition de contenu
- Les effets de survol (hover) sur les cœurs et les boutons
- Les transitions de validation des plats

---

### 📱 Mobile First

L’intégration a été pensée en **Mobile First** dès le départ :

- La structure HTML et les styles SCSS sont optimisés pour les petits écrans
- Des media queries progressives adaptent l’interface aux écrans tablette et desktop
- L’expérience utilisateur est fluide et cohérente sur tous les formats d’écrans

---

### 🧱 SCSS modulaire

L'organisation des styles suit une structure claire et maintenable :
scss/
│
├── base/ # Reset, typographies, variables globales
│ ├── _reset.scss
│ ├── _variables.scss
│ └── _mixins.scss
│
├── components/ # Boutons, loaders, cœurs, etc.
│ └── _components.scss
│
├── pages/ # Styles propres aux pages (home, menus)
│ ├── _home.scss
│ └── _menus.scss
│
├── utils/ # Animations, helpers
│ └── _animations.scss
│
└── main.scss # Fichier principal qui importe tous les autres

---

## 🔗 Live preview

Visualisez le projet en ligne :

👉 https://delia-1.github.io/p-3-oh-my-food-/

---

## 👩‍💻 Auteur

**Délia Knoepfli**
Développeuse web en formation chez OpenClassrooms⚡
