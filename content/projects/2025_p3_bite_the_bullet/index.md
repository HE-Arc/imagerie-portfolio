---
title: "Boids (2025)"
date: 2025-08-29
draft: false
description: "Jeu multijoueur local réalisé avec Godot. Inspiré de TowerFall Ascension et Stick Fight : The Game."
summary: "Jeu multijoueur local réalisé avec Godot. Inspiré de TowerFall Ascension et Stick Fight : The Game."
tags: ["3ème année", "Projet P3 HES d'été", "C++", "OpenGL"]
authors : ['Joey Schmied', "Julien Brechbühler", "Alexandre Guillaume"]
---

{{% columns ratio="3:1" class="space-x-4" %}} <!-- begin columns block -->

**Boids** est un simulateur d'entités se déplaçant selon le modèle de *Craig Reynolds* (Siggraph 1987).
Il est implémenté en C++ avec OpenGL pour le rendu graphique.
Il utilise les QuadTrees pour optimiser les calculs de voisinage entre les entités.
Il gère également l'évitement des collisions entre les entités et les obstacles.
Enfin, il intègre une GUI avec ImGui pour permettre à l'utilisateur de modifier les paramètres du modèle en temps réel.

{{< youtubeLite id="e2uPGnN11CY" label="Boids (2025)" >}}

<---> <!-- magic separator, between columns -->

<div class="[&>figure]:my-4">
{{< figure
src="gallery/image1.png"
>}}

{{< figure
src="gallery/image2.png"
>}}

{{< figure
src="gallery/image3.png"
>}}

{{< figure
src="gallery/image4.png"
>}}

</div>

{{% /columns %}}

{{< description P3HESEte >}}