# 📷 Comparaison d'approches algorithmiques  

## 📝 Général  

- **Version** : 0.1 (2024-01-12)  
- **Description** : Ce projet est un prototype d'application permettant d'effectuer diverses modifications sur des images selon la demande des utilisateurs.  

## 📌 Table des matières  

- [Lancement de l'application](#🚀-lancement-de-lapplication)  
- [Fonctionnalités et utilisation](#✨-fonctionnalités-et-utilisation)  

## 🚀 Lancement de l'application  

Avant d’exécuter le programme, assurez-vous que le projet contient les fichiers suivants :  

- `main.cpp`  
- `project_I.cpp`  
- `project_I.h`  

### 📂 Chargement d'une image  

Lors de l’exécution, le programme vous demande :  

> "Souhaitez-vous ouvrir un fichier PPM ou créer une image par vous-même ? Sélectionnez 1 ou 2."  

- **Option 1** : Charger une image existante au format `.ppm`. Vous devrez entrer le nom du fichier existant.  
- **Option 2** : Créer une nouvelle image. Vous devrez spécifier :  
  - Le nombre de lignes et de colonnes.  
  - Les composantes Rouge, Vert et Bleu (RGB) pour générer l’image.  

### 🛠️ Modification de l’image  

Une fois l’image chargée ou créée, un menu s’affiche avec différentes options de modification.  
Pour terminer le programme, entrez **22**.  

## ✨ Fonctionnalités et utilisation  

Le programme propose les fonctionnalités suivantes :  

| **Numéro** | **Action** |
|------------|-----------|
| 1 | Convertir l'image en **noir et blanc**. |
| 2 | Convertir l'image en **niveaux de gris**. |
| 3 | Appliquer un effet **rouge et noir**. |
| 4 | **Diminuer** la luminosité (valeur entre **0 et 1**). |
| 5 | **Augmenter** la luminosité (valeur **supérieure à 1**). |
| 6 | **Diminuer** le contraste (facteur entier **x**). |
| 7 | **Augmenter** le contraste (facteur entier **x**). |
| 8 | Simuler la **deutéranopie** (daltonisme). |
| 9 | Simuler la **protanopie** (daltonisme). |
| 10 | Simuler la **tritanopie** (daltonisme). |
| 11 | Rogner l'image **à gauche**. |
| 12 | Rogner l'image **à droite**. |
| 13 | Rogner l'image **en haut**. |
| 14 | Rogner l'image **en bas**. |
| 15 | **Rotation à droite**. |
| 16 | **Rotation à gauche**. |
| 17 | **Retournement horizontal** (symétrie verticale). |
| 18 | **Retournement vertical** (symétrie horizontale). |
| 19 | **Agrandir** l'image (facteur entier **x**). |
| 20 | **Réduire** l'image (facteur entier **x**). |
| 21 | Appliquer un effet de **flou** (valeur entre **1 et 3** : G3, Gaussien, Contour Sobel). |
| 22 | **Quitter** le programme. |
