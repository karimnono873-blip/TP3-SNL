# 📉 TP3 : Systèmes Non Linéaires - Premier Harmonique & Saturation

**Institution :** U.S.T.H.B / F.G.E. - [cite_start]Département d'Automatique [cite: 22, 23]
[cite_start]**Module :** Systèmes Non Linéaires (Année universitaire 2025-2026) [cite: 22, 23]
**Auteur :** DAHANE AHMED LAMINE  

---

## 📋 Description du Projet

[cite_start]Ce projet est une application web interactive complète développée pour résoudre et illustrer le TP N°3 portant sur la méthode du premier harmonique appliquée à une non-linéarité de type saturation[cite: 24, 25]. 

L'interface "Deep Space Edition" regroupe l'analyse théorique, la résolution numérique du système bouclé, et des visualisations interactives dans le domaine temporel et fréquentiel (plan complexe).

## ✨ Fonctionnalités Principales

* [cite_start]**📘 Théorie & Calculs Automatisés :** Explication détaillée du gain équivalent $N(a)$ pour la saturation (seuil $h=1.5$, gain $k=2$)[cite: 26]. [cite_start]Calcul théorique de la pulsation critique ($\omega_c$) et de l'amplitude du cycle limite ($a_c$)[cite: 43, 44].
* [cite_start]**🎯 Plan Complexe de Nyquist :** Tracé interactif du lieu de transfert du système linéaire $H(j\omega)$ et du lieu critique $-1/N(a)$ [cite: 35, 37, 39][cite_start], mettant en évidence leur point d'intersection[cite: 41].
* **⚙️ Simulateur RK4 Temps Réel :** Intégration numérique précise (Runge-Kutta 4) des équations d'état du système d'ordre 3 bouclé. [cite_start]Les curseurs permettent de modifier les conditions initiales ($x_1, x_2, x_3$) pour observer le comportement dynamique[cite: 29, 30, 32, 34].
* [cite_start]**📈 Visualisation Temporelle & Spatiale :** Tracés synchronisés de l'évolution de la sortie $x_1(t)$ et de sa trajectoire dans le plan de phase (vitesse vs position)[cite: 33].
* [cite_start]**💻 Script MATLAB Complet :** Inclusion du code source MATLAB officiel résolvant l'ensemble du cahier des charges (utilisation de `ode45`, `fzero`, `linspace`)[cite: 32, 36, 44].

## 🚀 Instructions d'Utilisation

L'application est "Single-Page" (SPA) et fonctionne directement dans le navigateur sans installation préalable.

1.  **Télécharger** le fichier `index.html`.
2.  **L'ouvrir** avec un navigateur web récent (Chrome, Firefox, Edge).
3.  **Explorer** les sections théoriques.
4.  **Ajuster** les curseurs des conditions initiales dans le panneau de contrôle et cliquer sur "Simuler le Système" pour observer l'attraction vers le cycle limite.

## 🛠️ Technologies Utilisées

* **Structure & Design :** HTML5, CSS3 (Thème sombre Cyber/Espace, Glassmorphism, Grilles CSS).
* **Logique Mathématique :** JavaScript (ES6+).
* **Rendu Scientifique :** [Plotly.js](https://plotly.com/javascript/) pour la génération des graphiques 2D (Nyquist, temporel, phase).

---
*Projet réalisé dans le cadre des travaux pratiques d'ingénierie en automatique.*
