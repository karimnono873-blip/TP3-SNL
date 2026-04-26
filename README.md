# 📉 TP3 : Systèmes Non Linéaires - Premier Harmonique & Saturation

**Institution :** U.S.T.H.B / F.G.E. - Département d'Automatique
**Module :** Systèmes Non Linéaires (Année universitaire 2025-2026)
**Auteur :** DAHANE AHMED LAMINE  

---

## 📋 Description du Projet

Ce projet est une application web interactive complète développée pour résoudre et illustrer le TP N°3 portant sur la méthode du premier harmonique appliquée à une non-linéarité de type saturation. 

L'interface "Deep Space Edition" regroupe l'analyse théorique, la résolution numérique du système bouclé, et des visualisations interactives dans le domaine temporel et fréquentiel (plan complexe).

## ✨ Fonctionnalités Principales

* **📘 Théorie & Calculs Automatisés :** Explication détaillée du gain équivalent pour la saturation. Calcul théorique de la pulsation critique et de l'amplitude du cycle limite.
* **🎯 Plan Complexe de Nyquist :** Tracé interactif du lieu de transfert du système linéaire et du lieu critique, mettant en évidence leur point d'intersection.
* **⚙️ Simulateur RK4 Temps Réel :** Intégration numérique précise (Runge-Kutta 4) des équations d'état du système d'ordre 3 bouclé. Les curseurs permettent de modifier les conditions initiales pour observer le comportement dynamique.
* **📈 Visualisation Temporelle & Spatiale :** Tracés synchronisés de l'évolution de la sortie et de sa trajectoire dans le plan de phase (vitesse vs position).
* **💻 Script MATLAB Complet :** Inclusion du code source MATLAB officiel résolvant l'ensemble du cahier des charges (utilisation de `ode45`, `fzero`, `linspace`).

## 🚀 Instructions d'Utilisation

L'application est "Single-Page" (SPA) et fonctionne directement dans le navigateur sans installation préalable.

1.  **Télécharger** le fichier `index.html`.
2.  **L'ouvrir** avec un navigateur web récent (Chrome, Firefox, Edge).
3.  **Explorer** les sections théoriques.
4.  **Ajuster** les curseurs des conditions initiales dans le panneau de contrôle et cliquer sur "Simuler le Système" pour observer l'attraction vers le cycle limite.

## 🛠️ Technologies Utilisées

* **Structure & Design :** HTML5, CSS3 (Thème sombre Cyber/Espace, Glassmorphism, Grilles CSS).
* **Logique Mathématique :** JavaScript (ES6+).
* **Rendu Scientifique :** Plotly.js pour la génération des graphiques 2D (Nyquist, temporel, phase).

---
*Projet réalisé dans le cadre des travaux pratiques d'ingénierie en automatique.*
