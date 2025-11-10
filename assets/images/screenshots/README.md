# 📱 Captures d'écran de l'application mobile

## Instructions pour ajouter les captures d'écran

Pour remplacer les images placeholder par les vraies captures d'écran de l'application :

### 1. Préparer les images

Nommez vos captures d'écran comme suit :
- `screenshot-home.png` - Écran d'accueil (bienvenue, catégories)
- `screenshot-chapters.png` - Liste des chapitres avec progression
- `screenshot-parts.png` - Liste des parties (Partie 1, 2, 3)
- `screenshot-quiz.png` - Écran de quiz
- `screenshot-prayer-times.png` - Horaires de prière
- `screenshot-tasbih.png` - Tasbih électronique

### 2. Dimensions recommandées

- **Format** : PNG ou JPG
- **Ratio** : 9:19 (format téléphone)
- **Résolution minimale** : 1080x2280 pixels
- **Taille optimale** : < 500KB par image

### 3. Optimiser les images

```bash
# Exemple avec ImageMagick (si installé)
convert screenshot-home.png -resize 1080x2280 -quality 85 screenshot-home-optimized.png
```

### 4. Mettre à jour index.html

Remplacez les chemins dans `index.html` :

```html
<!-- Ligne ~186 -->
<img src="assets/images/screenshots/screenshot-home.png" alt="Écran d'accueil AT-Taqwa" />

<!-- Ligne ~196 -->
<img src="assets/images/screenshots/screenshot-chapters.png" alt="Liste des chapitres" />

<!-- Ligne ~206 -->
<img src="assets/images/screenshots/screenshot-parts.png" alt="Parties du livre" />
```

### 5. Captures d'écran recommandées

Pour une présentation optimale, ajoutez :
1. **Écran d'accueil** - Montrant le message de bienvenue et les catégories
2. **Liste des chapitres** - Avec les barres de progression
3. **Liste des parties** - Montrant le contenu premium débloqué
4. **Écran de quiz** - Interface de quiz
5. **Horaires de prière** - Affichage des heures
6. **Tasbih** - Compteur de dhikr

---

**Note** : Les images actuelles sont des placeholders. Remplacez-les par les vraies captures d'écran pour une meilleure présentation.

