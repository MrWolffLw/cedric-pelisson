
# 🌐 Portfolio de Cédric Pélisson — Améliorations Visuelles

Ce document décrit les pistes d'améliorations visuelles modernes à intégrer à la page personnelle de Cédric Pélisson, dans le but d'attirer l'attention des recruteurs et de valoriser son profil de développeur web.

---

## 🎨 Identité visuelle moderne

- **Palette de couleurs professionnelle** :
  - Bleu nuit `#1e2a38`
  - Blanc cassé `#f8f9fa`
  - Accent turquoise `#2ed3b7`
  - Texte foncé `#2c3e50`

- **Typographies élégantes** :  
  Intégrer Google Fonts comme :
  - [`Poppins`](https://fonts.google.com/specimen/Poppins)
  - [`Montserrat`](https://fonts.google.com/specimen/Montserrat)
  - [`Inter`](https://fonts.google.com/specimen/Inter)

  Exemple d'intégration :
  ```html
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>body { font-family: 'Poppins', sans-serif; }</style>
  ```

---

## 👤 Présentation personnelle

- **Bannière de présentation** avec fond dégradé :
  ```css
  .hero {
    background: linear-gradient(to right, #1e2a38, #2ed3b7);
    color: white;
    padding: 80px 0;
  }
  ```

- **Section "À propos" avec photo professionnelle** :
  - Photo à gauche, texte bio à droite (flexbox responsive)
  - Ajout d'un petit slogan ou accroche

---

## 💼 Mise en valeur des compétences

- **Badges animés** pour chaque compétence (HTML, CSS, JS, etc.)
- **Barres de progression** ou **radars** de compétences
- **Icônes** ou logos des technologies (via [Devicon](https://devicon.dev))

- **Timeline verticale** pour les expériences et formations :
  - Lisible, fluide sur mobile
  - Animation d’apparition au scroll (cf. AOS)

---

## 🧩 Éléments visuels modernes

- **Cartes avec effet hover** :
  ```html
  <div class="card shadow p-3 mb-4 rounded">
    <img src="img/project.png" class="card-img-top">
    <div class="card-body">
      <h5>Dashboard React</h5>
      <p>Un projet de tableau de bord interactif avec Firebase.</p>
    </div>
  </div>
  ```

- **Illustrations vectorielles modernes** :
  - Utiliser [Undraw](https://undraw.co/) ou [LottieFiles](https://lottiefiles.com/)

---

## 🔥 Bonus attractivité

- ✅ **Bouton "Télécharger mon CV"** bien visible
- ✅ **Section “Pourquoi me recruter ?”** :
  - Liste de qualités (Curieux, Humain, Organisé...)
  - Icônes associées
- ✅ **Témoignages / recommandations** (optionnel)

---

## 🧠 Interactions et animations

- Intégrer [AOS](https://michalsnik.github.io/aos/) pour les animations au scroll :
  ```html
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <script>AOS.init();</script>
  ```

- Animation d’apparition pour chaque bloc :
  ```html
  <div data-aos="fade-up">...</div>
  ```

- Ajout d’une **barre de progression de scroll** en haut :
  ```css
  #progressBar {
    position: fixed;
    top: 0; left: 0;
    height: 4px;
    background: #2ed3b7;
    z-index: 9999;
  }
  ```

- **Menu mobile responsive** avec bouton burger

---

## 📱 Responsive design

- Design fluide pour smartphones / tablettes
- Navigation simplifiée sur mobile
- Police adaptée selon l’écran (`clamp()` en CSS)

---

## 📌 Bonus techniques

- Ajouter des balises `meta` pour le SEO
- Favicon personnalisé
- Lien vers profil LinkedIn, GitHub
- Ajout d’un formulaire de contact fonctionnel

---

## 🛠️ Prochaine étape

- [ ] Appliquer les styles ci-dessus dans `index.html`
- [ ] Ajouter les assets (photos, CV, icônes)
- [ ] Créer une version Figma + vidéo démo du portfolio

---

👨‍💻 _Rédigé pour optimiser l’attractivité de ton portfolio et valoriser ton profil auprès des recruteurs._
