# 📘 TP1 - Computer Vision

## 🎯 Objectif du projet
Ce projet a pour objectif d’appliquer les principales techniques de Vision par Ordinateur
vues en cours à travers une série d’exercices pratiques implémentés en Python avec OpenCV.
Tous les exercices sont regroupés dans un seul notebook Google Colab.

---

## 🗂 Structure du projet

```text
TP1-ComputerVision/
│
├── README.md
├── TP1-ComputerVision.ipynb
│
└── images/
```
---
## 🧪 Contenu du notebook

### 1. Niveaux de gris
- Conversion d’une image en niveaux de gris  
- Comparaison entre l’image originale et l’image en niveaux de gris  
- Détection du pixel le plus lumineux pour identifier la source de lumière  
- Discussion sur l’intérêt des niveaux de gris pour la détection de mouvement  

---

### 2. Espaces de couleurs
- Conversion de l’image du format BGR vers l’espace HSV  
- Création de masques pour les couleurs rouge, orange et vert  
- Détection automatique de la lumière du feu tricolore allumée  

---

### 3. Dessin sur des images
- Dessin d’un rectangle autour du ballon  
- Ajout d’une flèche indiquant la direction du tir  
- Insertion d’un texte indiquant la vitesse du tir  

---

### 4. Transformations géométriques
- Estimation de l’angle d’inclinaison d’une image prise de travers  
- Application d’une rotation inverse pour redresser la scène  
- Comparaison visuelle entre l’image avant et après transformation  

---

### 5. Redimensionnement, interpolation et recadrage
- Redimensionnement d’une image produit en 512 × 512  
- Recadrage pour centrer l’objet dans un carré parfait  
- Création de miniatures (128 × 128) en testant plusieurs méthodes d’interpolation  

---

### 6. Histogrammes et seuillage
- Analyse de l’histogramme initial d’une image à faible contraste  
- Application d’une égalisation d’histogramme pour améliorer le contraste  
- Réalisation d’un seuillage automatique à l’aide de la méthode d’Otsu  

---

### 7. Rehaussement d’images
- Application d’une correction gamma pour éclaircir les zones sombres  
- Visualisation de l’histogramme après correction  
- Augmentation légère du contraste  
- Comparaison entre l’image originale et l’image rehaussée  

---

### 8. Convolutions, bruit et filtrage
- Application d’un flou gaussien pour réduire le bruit  
- Utilisation d’un filtre de netteté pour restaurer les détails  
- Ajout artificiel de bruit sur une image initialement nette  
- Étude des différents types de bruit et des filtres adaptés à leur réduction  
