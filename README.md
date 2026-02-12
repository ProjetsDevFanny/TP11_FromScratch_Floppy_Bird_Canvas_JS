# Floppy_Bird en JavaScript Vanilla

Jeu video 2D : faire voler l'oiseau sans le faire tomber ni toucher les tuyaux.

Bienvenue dans ma version personnalisée de **Flappy Bird**, développée de A à Z en JavaScript sans framework, avec HTML5 CSS3 Canvas. Ce projet met en œuvre la logique de jeu 2D, l’animation par sprites, la gestion d’événements clavier/souris, le système de score, la persistance locale, et l'intégration de sons d’ambiance.

## Objectif du projet

- Approfondir ma maîtrise de **JavaScript natif**, en particulier :
- Les animations via `requestAnimationFrame`
- Le rendu sur le canvas HTML5, avec mouvements des éléments et positionnement aléatoire des tuyaux
- Créer des rectangles de "debugages" en canvas pour mieux visualiser la zone de collision oiseau/tuyaux
- Comprendre les boucles de jeu en temps réel
- Gérer les ressources (sprites, sons)
- Améliorer l’expérience utilisateur par des interactions fluides

## Fonctionnalités clés

- **Gameplay fluide** : contrôle à la souris (clic) ou au clavier (flèche haut/bas)
- **Animation par sprites** : battement d’ailes de l’oiseau, fond défilant
- **Collisions précises** avec les tuyaux
- **Recyclage des tuyaux** pour un gameplay infini
- **Meilleur score sauvegardé** dans le localStorage
- **Ambiance sonore** : fond musical + effets sonores personnalisés

## Aperçu

![Flappy Bird Preview](./Screen%20Shot2_Floppy%20Bird.png)

## Demo animée

https://projetsdevfanny.github.io/TP11_FromScratch_Floppy_Bird_Canvas_JS/

## Lancer le jeu

1. Clone ce repo :

   ```bash
   git clone git@github.com:ProjetsDevFanny/TP11_FromScratch_Floppy_Bird_Canvas_JS.git (SSH)
   ou git clone https://github.com/ProjetsDevFanny/TP11_FromScratch_Floppy_Bird_Canvas_JS.git (HTTPS)

   ```

2. Ouvrez le fichier index.html dans votre navigateur.

3. Cliquez sur la page d'accueil, puis appuiez sur ↑ ou ↓ ou pour commencer à jouer !

## Stack technique

- HTML5 + CSS3 (structure et style minimaliste)
- JavaScript Vanilla (aucune librairie externe)
- Canvas 2D
- Gestion des assets audio/visuels en local
- localStorage pour persister les scores

## Ce que j’ai appris

- Comment structurer un jeu 2D simple sans moteur de jeu
- Le changement d'état du jeu (entre page d'accueil et la page du jeu)
- L’importance du timing et de la boucle de rendu
- Gérer des événements clavier/souris sans interférence
- Déboguer visuellement avec des hitboxes et des rectangles de collision
- Optimiser la performance avec le recyclage d’objets

## Pistes d'amélioration

- Ajouter une difficulté progressive (accélération des tuyaux, rétrécissement du gap)
- Implémenter un système de pause
- Ajouter un menu "Game Over" avec bouton replay
- Rendre le jeu responsive sur mobile
